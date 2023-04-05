
Welcome to the one and only Universal RepackBoot v1.0 by lebigmac ( Android Boot.img Repacker )

OFFICIAL WEBSITE :
=======================
http://www.systemrw.com
=======================

More info:
----------
Original author: lebigmac
Additional credits: AOSP, Osm0sis, Osvcos ( mkbootimg and unpackbootimg originally sourced from https://github.com/osm0sis/mkbootimg )
Shout-outs: TheGhost1951, sekaiacg, Yuki1001, thka2016, lopestom, Foxhackerr, Munjeni, Kolibass, keven11, frxhb, baxal0, harpreet.s, HemanthJabalpuri and many more!
Creation date: March 2023
Last updated: April 2023
Short description: Automatically repack & flash your boot image to your device
Long description: This program extracts the required parameters from the specified source folder and dynamically generates a new set of arguments which are then plugged into mkbootimg to generate a brand new patched_boot.img that can also be auto-flashed with the -flash switch ;)

Options:
--------
*) Specify the source directory [ -i /path/to/src/dir ]

*) Specify the output file [ -o img/patched_boot.img ]

*) Auto-Flash the patched_boot.img directly to your device [ -flash ]

Example:
--------
Generate new patched_boot.img file based on source directory and flash it directly to your boot block device:
bin/repackboot -i /path/to/src/dir -o img/patched_boot.img -flash

