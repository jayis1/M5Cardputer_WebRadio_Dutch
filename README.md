# M5Cardputer WebRadio Danish version

See the ino file for the web-streams.

## Firmware
The latest compiled firmware is available as `M5Cardputer_WebRadio_danish.bin`.

## Libraries

M5Cardputer_WebRadio needs these Libraries:

* M5Unified : https://github.com/m5stack/M5Unified
* ESP8266Audio: https://github.com/earlephilhower/ESP8266Audio
* M5Cardputer
* M5GFX

![image](https://github.com/rolandbreedveld/M5Cardputer_WebRadio_Dutch/blob/main/M5Cardputer_WebRadio_NL.jpeg)
----
WiFi Settings will be stored in EEPROM

## Compilation

Arduino Compiler options:

* Select Board: M5Stack -> M5StampS3
* Partition Scheme: "No OTA(2MB APP/2MB FATFS)"
* Write the bin file: Sketch -> "Export Compiled Binary"
