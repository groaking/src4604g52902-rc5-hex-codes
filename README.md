# SRC4604G52902 PTZ Remote Control Signal Codes

> For Magnustek PTZ (Pan-Tilt-Zoom) CCTV Cameras
> ![src4604g52902](https://github.com/groaking/src4604g52902-rc5-hex-codes/assets/93555329/f5a89f71-e3a7-484a-8032-612a88be15d7)
> 
> This infrared remote controller uses RC5/RC-5 protocol with 13 bits of MSB-first
> 
> The three "Camera Select" buttons in the picture changes the RC5 signal encoding of the SRC4604G52902 remote control, so we divide them into three separate sections
> 
> You can buy this remote on [eBay](https://www.ebay.com/itm/235482752255)

## Mode: Camera 1

| Button Name         | Address (HEX) | Command (HEX) |
|:-------------------:|:-------------:|:-------------:|
| Reset               | `0x9`         | `0xC`         |
| Power               | `0x9`         | `0xD`         |
| Cam. Select 1       | `0x8`         | `0x3B`        |
| Cam. Select 2       | `0x8`         | `0x23`        |
| Cam. Select 3       | `0x8`         | `0xE`         |
| Preset 1            | `0x9`         | `0x1`         |
| Preset 2            | `0x9`         | `0x2`         |
| Preset 3            | `0x9`         | `0x3`         |
| Preset 4            | `0x9`         | `0x4`         |
| Preset 5            | `0x9`         | `0x5`         |
| Preset 6            | `0x9`         | `0x6`         |
| Preset 7            | `0x9`         | `0x7`         |
| Preset 8            | `0x9`         | `0x8`         |
| Preset 9            | `0x9`         | `0x9`         |
| Preset - Set        | `0x9`         | `0x27`        |
| Preset - Clear      | `0x9`         | `0x0`         |
| Preset - Call       | `0x9`         | `0x2D`        |
| Zoom Fast Plus (+)  | `0x9`         | `0x10`        |
| Zoom Fast Minus (-) | `0x9`         | `0x11`        |
| OSD - Dome          | `0x9`         | `0x29`        |
| OSD - Lens          | `0x9`         | `0x22`        |
| Zoom Slow Plus (+)  | `0x9`         | `0x20`        |
| Zoom Slow Minus (-) | `0x9`         | `0x21`        |
| Auto                | `0x9`         | `0x3F`        |
| Manual              | `0x9`         | `0x33`        |
| Far                 | `0x9`         | `0x35`        |
| Near                | `0x9`         | `0xA`         |
| Arrow Up            | `0x9`         | `0x12`        |
| Arrow Left          | `0x9`         | `0x15`        |
| Arrow Right         | `0x9`         | `0x16`        |
| Arrow Down          | `0x9`         | `0x13`        |
| Enter               | `0x9`         | `0x14`        |
| L-Limit             | `0x9`         | `0x31`        |
| Scan                | `0x9`         | `0x32`        |
| R-Limit             | `0x9`         | `0x18`        |
| Home                | `0x9`         | `0x37`        |
| Tour                | `0x9`         | `0x36`        |
| Rev                 | `0x9`         | `0x34`        |
| Freeze              | `0x9`         | `0x2B`        |
| BL                  | `0x9`         | `0x3E`        |
| WB                  | `0x9`         | `0x3D`        |
| AE                  | `0x9`         | `0x2C`        |
| DZOOM               | `0x9`         | `0x3A`        |
| HDMI                | `0x9`         | `0x17`        |
| DVI                 | `0x9`         | `0x26`        |
| Format              | `0x9`         | `0x25`        |

## Mode: Camera 2

| Button Name         | Address (HEX) | Command (HEX) |
|:-------------------:|:-------------:|:-------------:|
| Reset               | `0xA`         | `0xC`         |
| Power               | `0xA`         | `0xD`         |
| Cam. Select 1       | `0x8`         | `0x3B`        |
| Cam. Select 2       | `0x8`         | `0x23`        |
| Cam. Select 3       | `0x8`         | `0xE`         |
| Preset 1            | `0xA`         | `0x1`         |
| Preset 2            | `0xA`         | `0x2`         |
| Preset 3            | `0xA`         | `0x3`         |
| Preset 4            | `0xA`         | `0x4`         |
| Preset 5            | `0xA`         | `0x5`         |
| Preset 6            | `0xA`         | `0x6`         |
| Preset 7            | `0xA`         | `0x7`         |
| Preset 8            | `0xA`         | `0x8`         |
| Preset 9            | `0xA`         | `0x9`         |
| Preset - Set        | `0xA`         | `0x27`        |
| Preset - Clear      | `0xA`         | `0x0`         |
| Preset - Call       | `0xA`         | `0x2D`        |
| Zoom Fast Plus (+)  | `0xA`         | `0x10`        |
| Zoom Fast Minus (-) | `0xA`         | `0x11`        |
| OSD - Dome          | `0xA`         | `0x29`        |
| OSD - Lens          | `0xA`         | `0x22`        |
| Zoom Slow Plus (+)  | `0xA`         | `0x20`        |
| Zoom Slow Minus (-) | `0xA`         | `0x21`        |
| Auto                | `0xA`         | `0x3F`        |
| Manual              | `0xA`         | `0x33`        |
| Far                 | `0xA`         | `0x35`        |
| Near                | `0xA`         | `0xA`         |
| Arrow Up            | `0xA`         | `0x12`        |
| Arrow Left          | `0xA`         | `0x15`        |
| Arrow Right         | `0xA`         | `0x16`        |
| Arrow Down          | `0xA`         | `0x13`        |
| Enter               | `0xA`         | `0x14`        |
| L-Limit             | `0xA`         | `0x31`        |
| Scan                | `0xA`         | `0x32`        |
| R-Limit             | `0xA`         | `0x18`        |
| Home                | `0xA`         | `0x37`        |
| Tour                | `0xA`         | `0x36`        |
| Rev                 | `0xA`         | `0x34`        |
| Freeze              | `0xA`         | `0x2B`        |
| BL                  | `0xA`         | `0x3E`        |
| WB                  | `0xA`         | `0x3D`        |
| AE                  | `0xA`         | `0x2C`        |
| DZOOM               | `0xA`         | `0x3A`        |
| HDMI                | `0xA`         | `0x17`        |
| DVI                 | `0xA`         | `0x26`        |
| Format              | `0xA`         | `0x25`        |

## Mode: Camera 3

| Button Name         | Address (HEX) | Command (HEX) |
|:-------------------:|:-------------:|:-------------:|
| Reset               | `0xB`         | `0xC`         |
| Power               | `0xB`         | `0xD`         |
| Cam. Select 1       | `0x8`         | `0x3B`        |
| Cam. Select 2       | `0x8`         | `0x23`        |
| Cam. Select 3       | `0x8`         | `0xE`         |
| Preset 1            | `0xB`         | `0x1`         |
| Preset 2            | `0xB`         | `0x2`         |
| Preset 3            | `0xB`         | `0x3`         |
| Preset 4            | `0xB`         | `0x4`         |
| Preset 5            | `0xB`         | `0x5`         |
| Preset 6            | `0xB`         | `0x6`         |
| Preset 7            | `0xB`         | `0x7`         |
| Preset 8            | `0xB`         | `0x8`         |
| Preset 9            | `0xB`         | `0x9`         |
| Preset - Set        | `0xB`         | `0x27`        |
| Preset - Clear      | `0xB`         | `0x0`         |
| Preset - Call       | `0xB`         | `0x2D`        |
| Zoom Fast Plus (+)  | `0xB`         | `0x10`        |
| Zoom Fast Minus (-) | `0xB`         | `0x11`        |
| OSD - Dome          | `0xB`         | `0x29`        |
| OSD - Lens          | `0xB`         | `0x22`        |
| Zoom Slow Plus (+)  | `0xB`         | `0x20`        |
| Zoom Slow Minus (-) | `0xB`         | `0x21`        |
| Auto                | `0xB`         | `0x3F`        |
| Manual              | `0xB`         | `0x33`        |
| Far                 | `0xB`         | `0x35`        |
| Near                | `0xB`         | `0xA`         |
| Arrow Up            | `0xB`         | `0x12`        |
| Arrow Left          | `0xB`         | `0x15`        |
| Arrow Right         | `0xB`         | `0x16`        |
| Arrow Down          | `0xB`         | `0x13`        |
| Enter               | `0xB`         | `0x14`        |
| L-Limit             | `0xB`         | `0x31`        |
| Scan                | `0xB`         | `0x32`        |
| R-Limit             | `0xB`         | `0x18`        |
| Home                | `0xB`         | `0x37`        |
| Tour                | `0xB`         | `0x36`        |
| Rev                 | `0xB`         | `0x34`        |
| Freeze              | `0xB`         | `0x2B`        |
| BL                  | `0xB`         | `0x3E`        |
| WB                  | `0xB`         | `0x3D`        |
| AE                  | `0xB`         | `0x2C`        |
| DZOOM               | `0xB`         | `0x3A`        |
| HDMI                | `0xB`         | `0x17`        |
| DVI                 | `0xB`         | `0x26`        |
| Format              | `0xB`         | `0x25`        |
