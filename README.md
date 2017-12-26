PS2 Netemu Selector
==========================

Application for changing ps2_netemu file versions on firmware 4.81, 4.82 (CEX, DEX, DECR (decr untested)). 
Based on modified version of XMB Manager Plus (XMBM+) Installer. 
Probably never gonna be updated. For original installer readme check file "READMEinstaller.markdown" 

## Usage

Install pkg file. Open application, and follow onscreen instuctions.

## Available versions

- Default - Clean emulator without additional features. Only standard cobra patches are applied.
- Temperatures Mod - Custom emulator version patched by 3141card to show temperatures of CELL/RSX while playing PS2 games. Additionally patched by me to fix temps display on every display mode, and set to refresh temp every 2 seconds.
- Memory Dumper Mod - Custom emulator version patched by 3141card to allow LV1 memory dump while playing PS2 games. Additionally this emu can use all HV calls, and have debug menu unlocked without need to use combo.
- HDD Browser Mod - Not really sure what is usage of this emu :D Looks like it allow you to select game image without need of cobra. 

Work only on 4.81, 4.82 cobra and non cobra firmware. App is changing files on dev_flash!

## Changes from Installer to Selector

- Obviously renamed project
- Removed reboot prompt for devflash operations (not needed for netemu change) 
- Fixed string centering in menus (ugly hack)
- Graphical changes (strings, colors, target names, etc.)
- Changed usleep values for buttons 
- Changed way of naming backups folder. Previous method resulted here in GO TO EMULATOR SELECTOR in name.
- Removed some refers to variable names in dialogs. Specially app_choice ones.
- More that I forgot, anyway source is here 

## Build

- Same requirements like originall installer but require custom ps2_netemu.self files to be added, and empty.txt to be removed, before pkg compilation.

## Credits

- andreus, and XMBM+ Team for great installer
- 3141card for r.e. and patches to ps2_netemu

Visit Git (Installer): https://github.com/XMB-Manager-Plus/xmb-manager-plus-installer
