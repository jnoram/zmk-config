These overlays bind ZMK's ext_power to Pro Micro pin 13 (nice!nano P0.13)
so the Sofle OLED header VCC rail can be switched on from firmware.

Place these two files at: boards/shields/
 - sofle_left.overlay
 - sofle_right.overlay

Use these build targets (GitHub Actions or west):
 - DS HIELD="sofle_left nice_view_adapter nice_view"
 - DS HIELD="sofle_right nice_view_adapter nice_view"
