# Description #
This is an unofficial repository containing supporting resources for the Ideaspark ESP32 1.14 inch LCD screen board. I created this repository to help centralize the disparate documentation and resources across the web.  I hope this will help other developers quickly get started working with the board.
# Contents #
This respository contains:
1. the minimal graphics example code taken from
    * https://github.com/GJKJ/ESP32114LCD/tree/main
3. static copy of the Adafruit library code taken from
    * https://github.com/adafruit/Adafruit-ST7735-Library/tree/master
    * https://github.com/adafruit/Adafruit-GFX-Library
4. documentation taken from the vendor's page
    * https://www.amazon.com/dp/B0D7S7YQMC
# Getting Started #
To run the code, open the "minimal_graphics_example.ino" folder in the Arduino IDE and follow photo instructions in the "docs" folder.
# License #
Respect the original license terms provided by the vendor, manufacturer, and for the Adafruit graphics libraries.
# Vendor Board Description #
- Brand: ideaspark
- Connectivity Technology: USB
- Included Components: board
- Operating System: Linux
- CPU Manufacturer: Espressif
- Wireless Communication Standard: 802.11bgn
- Compatible Devices: 	Various IoT devices
- RAM Memory Technology: 	LPDDR4
- Processor Count:	2
- Total Usb Ports: 1

The ESP32 1.9'' LCD board has all the features of the traditional ESP32 Devkit V1 module,with the same exact peripheral ports,offers seamless integration with a 1.14-inch LCD display, eliminating the need for frustrating wires and breadboards.Display features a high-resolution 135x240 full color with ST7789 driver and is compatible with I2C interfaces. Plus,It uses Type-c usb cable to connect. Say goodbye to messy setups and hello to hassle-free electronics with the ESP32 board.

Board is based on ESP32-WROOM-32 module integrated with Antenna switches, RF Balun, power amplifiers, low-noise amplifiers, filters, and management modules, and the entire solution occupies the least area of PCB. 2.4 GHz Wi-Fi plus BLE dual-mode chip, TSMC Ultra-low power consumption 40nm technology, power dissipation performance and RF performance is the best, safe and reliable, easy to extend to a variety of applications

Board uses SPI to connect LCD: D23/GPIO23->MOSI, D18/GPIO18->SCLK, D15/GPIO15->CS, D2/GPIO2->DC, D4/GPIO4->RST,D32/GPIO32->BLK.With this board,it's easy to display a variety of information and data
To install the new version driver for CH340,simply search for the keywords "CH340 Driver" on Google.com or Bing.com and follow the installation instructions provided.Recommended for Win10 Operating System

This board is an outstanding option for various Internet of Things (IoT) projects. It can be used to display network connection status,monitor information, power levels, and other relevant data. Additionally, it's suitable for building Internet Weather Stations, Graphic Plotter, Data Monitor, and Other similar applications

# External
[Devkit V1 Documentation](https://www.circuitstate.com/pinouts/doit-esp32-devkit-v1-wifi-development-board-pinout-diagram-and-reference/)
[Processor Datasheet](https://www.espressif.com/sites/default/files/documentation/esp32-wroom-32e_esp32-wroom-32ue_datasheet_en.pdf)