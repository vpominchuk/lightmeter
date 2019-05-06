# lightmeter
A Lightmeter/Flashmeter for photographers, based on Arduino.

Components:
1. Arduino NANO v.3
2. BH1750 light sensor
3. SSD1306 128*64 OLED SPI Display
4. Buttons

Thanks @morozgrafix https://github.com/morozgrafix for creating schematic diagram for this device.

The lightmeter based on Arduino as a main controller and BH1750 as a metering cell. Information is displayed on SSD1306 OLED display. The device is powered by 2 AAA batteries.

Functions list:

* Ambient light metering
* Flash light metering
* ND filter correction
* Aperture priority
* Shutter speed priority
* ISO range 8 - 4 000 000
* Aperture range 1.0 - 3251
* Shutter speed range 1/10000 - 133 sec
* ND Filter range ND2 - ND8192
* Displaying amount of light in Lux.
* Displaying exposure value, EV
* Recalculating exposure pair while one of the parameter changing
* Battery information
* Power 2xAAA LR03 batteries

Detailed information on my site: https://www.pominchuk.com/lightmeter/
