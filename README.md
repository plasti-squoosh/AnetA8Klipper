# AnetA8Klipper
This is my journey of making an Anet A8 more modern and functional

I currently have a more or less stock Anet A8 purchased many years ago.

The Hardware Mods are as follows:
  1. Big Tree Tech SKR Mini E3 V3 control Board
  2. Big Tree Tech TFT35 screen
  3. BMG Clone Extruder
  4. Clone V6 Hotend
  5. Filament Sensor
  6. BLTouch Clone
  7. Bed Heater Cable Chain
  8. Front Frame Brace
  9. Middle Frame Brace
  10. Rear Frame Brace
  11. Ball Screw Caps
  12. Y Belt Tensioner
  13. X Belt Tensioner
  14. Custom X carriage

I am running Klipper on the printer with a Raspberry Pi 3B as my server. This Raspberry Pi also serves one other printer.

Currently trying to hunt down a problem where the printer randomly hangs and crashes both itself and the Pi server.
I'm going to upload my current configuration files and try to load and modify most of the config from my other printer that appears to function well. I hope that it is as simple as some .cfg files being malformed.

I have replaced the following trying to fix this issue:
  1. Pi Sd Card
  2. Pi Power Supply
  3. Pi to Printer Micro USB

I have tried these steps to fix the issue:
  1. New install of klipper os
  2. new install of linux with new kiauh klipper server
  3. checked all wires and connections on printer
  4. disconnected the UART cable for the TFT 35
  5. tried tuning motors and drivers
  6. tried slowing prints down
  7. modification of slicer settings, but may try this again. it could be that simple
