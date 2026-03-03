1- Download NP2 for PSP (https://www.gamebrew.org/wiki/NP2_for_PSP_by_hissorii)

1.1- Extract "NP2_for_PSP_v0.39" and "NP21_for_PSP_v0.39"

1.2- Rename the folders "NP2" and "NP21"

2- Download the repository for easy configuration (at the top right of the files, click 'Code' then 'Download ZIP')

2.1- Merge "NP2" and "NP21" folders with the ones from before

3- Install by dropping "NP2" and "NP21" folders in "ux0:/pspemu/PSP/GAME/"

4- Install your games inside the "NP2" folder

To load game, go to Menu > FDD1/FDD2/HDD > Open..., then from Emulation > Reset.

Notes:

Included in the CFG zip folder are also two Adrenaline Bubble Manager presets to make them look better in your homescreen

Settings in the NP21 version are not saved on exit, so you need to edit its CFG to change it permanently

Some games like Touhou require you to use Neko Project 21 but are too demanding for it so they will not run well (if only we could increase the clock rate further)

You can also change the GDC clock by altering the 5th line of the config from

5MHz:

`DIPswtch=3e 73 7b`

to 2.5MHz:

`DIPswtch=3e f3 7b`

Some games might need this to boot properly

Here is a great archive of most if not all english translated titles on the PC-98: (https://archive.org/details/nec-pc-9801-translations).
