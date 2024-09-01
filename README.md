# FluidNC-Controller

FluidNCC – GRBL controller based on ESP-WROOM-32 module, for small CNC machines. Designed for [FluidNC firmware](https://github.com/bdring/FluidNC).

[Source files for EasyEDA](Sources)

[Ready schematics and PCB files](Export)

[Gerber files for production](Gerber)

__Features:__

* Separate power source inputs for logic (12..32V) and Spindle (12..48V). You can join it together by soldering J1 jumper (but 32V input voltage limit in this case).
* Opto-coupled PWM for spindle.
* PWM output for laser.
* Support up to 4 (X,Y1,Y2,Z axis) step motor drives TMC-2209 in UART mode.
* I2C OLED Display.
* 5V cooling fan connector.
* Micro SD.
* X,Y,Z Axis end-stops connectors.
* Z-Probe connector.
* Emergency button connector.

Example configuration for CNC-3018 in [config.yaml](config.yaml) file.

Photos of previous version (v1.0 and v2.0.1): 

![Version 2 and 1](/Export/v2_and_v1.jpg)

![Mounted on CNC-3018 Pro metal](/Export/on-cnc3018.jpg)

2024-09-01 Current version v2.0.2 - bug fixes for v2.0.1. I haven't build it yet.