# HDMI Mod by Matthias "Ba" Prögel
Matthias is the creator of the builds with serial numbers [0009](https://commodorepetmini.com/user-builds#0009) and 0010 [0010](https://commodorepetmini.com/user-builds#0010), and is also responsible for a mod to make the Commodore PET Mini work with a small HDMI display instead of the official SPI display. Here's more information about his HDMI mod: https://commodorepetmini.com/contribute/hdmi-mod

This directory contains the STL model files Matthias has modified to fit the HDMI display. This are the modificatons he made:

- **Monitor frame** To fit the new display.
- **Monitor frame holder** To hold the display in place with two M3-screws.
- **Monitor housing** Cut-out for the HDMI socket.
- **Monitor stand** Cut-out for the HDMI socket.

Since the display is rotated 180 degreess, the following additional modification have to be made in `/boot/config.txt`

```
overscan_scale=1
display_rotate=2
overscan_left=18
overscan_right=95
overscan_top=16
overscan_bottom=16
```