# Raspberry Pi Chainload Scripts
Bootloader scripts for the booting the Raspberry Pi


## Building a U-Boot script into an image
To create an image from a U-Boot script, run the below command

  mkimage -A arm -T script -C none -n "Ubuntu boot script" -d bootscr.rpi boot.scr
