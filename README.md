# HevORT HVT0097

This repo contains data on HVT0097. 


![HVT0097](./images/HVT0097.jpg)

## Config

Klipper configs for HVT0097 (HD12 315x315x340) printer running fluidd.

Macros and config files are separeted in the folders.

## Main electronics

- Mainboard: Octopus Pro w/ TMC2209
- A/B motors: E3D High Torque Motor
- Z motors: E3D Super Whopper Motor
- XYZ rails: CNA w mediumn preload
- Ballscrews: [SFU1204](https://www.aliexpress.com/item/1005001303680673.html)
- Host: Raspberry Pi 4B 8GB w/ [active cooling](https://www.amazon.se/gp/product/B08B84D8VH/ref=ppx_yo_dt_b_asin_title_o08_s00?ie=UTF8&th=1)
- PSU 24v: Mean well ‎NDR-240-24‎
- PSU 5v: Mean well MDR-40-5
- Display: Type B Mini 12864 Display
- Replay: [Shelly 1PM+](https://github.com/jontek2/HVT0097-klipper_config/blob/main/moonraker.conf#L44-L50)
- CAN: BTT EBB36 v1.2 w/ BTT U2C
- Camera: USB Camera Module 120 degree Wide Angle OV5640

## Toolhead
- Hotend: Rapido UHF
- Toolhead: Mantis toolhead w/ sherpa mini extruder
- Hotend fan: Sunon MF30060V21000UA99
- Partcooling fan: 2 of GDStime 5015
- Extruder motor: LDO-36STH20-1004AHG

## Bed
- Heater pad: Keenovo silicone AC heater (300mm x 300mm 600W 220V/240V)
- SSR: Omron G3NA-210B-UTU-DC5-24
- Buildplate: Custom 340x340x8mm buildplate 

## Other

- Display: Mini 12864 LCD
- Emergency stop button

## Modifications

- Custom enclosure
- Custom skirts
- Frame thermistor
- Electronics bay thermistor
- [Nevermore v5 duo](https://github.com/nevermore3d/Nevermore_Micro/tree/master/V5_Duo/V2)
- [Voron Switchwire spool holder](https://github.com/VoronDesign/Voron-Switchwire/blob/master/STL/spool_holder_base.stl)
- [Voron LED Bar Clip - Remixed for 3030 from https://bit.ly/3CkBe5D](/mods/LED_bar_clip/)
- [Z umbilical](/mods/Z-umbilical/)
- [Voron Trident DIN mount- Remixed for 3030 from https://bit.ly/3tEoLph](/mods/DIN_frame_mount/)