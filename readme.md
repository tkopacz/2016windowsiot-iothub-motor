# Remarks 

Used chip: TB6612 (Motor) + PCA9685 (PWM)

TB6612: http://toshiba.semicon-storage.com/info/lookup.jsp?pid=TB6612FNG&lang=en
PCA9685: [http://cache.nxp.com/documents/data_sheet/PCA9685.pdf?fpsp=1&WT_TYPE=Data Sheets&WT_VENDOR=FREESCALE&WT_FILE_FORMAT=pdf&WT_ASSET=Documentation&fileExt=.pdf](http://cache.nxp.com/documents/data_sheet/PCA9685.pdf?fpsp=1&WT_TYPE=Data Sheets&WT_VENDOR=FREESCALE&WT_FILE_FORMAT=pdf&WT_ASSET=Documentation&fileExt=.pdf "http://cache.nxp.com/documents/data_sheet/PCA9685.pdf?fpsp=1&WT_TYPE=Data Sheets&WT_VENDOR=FREESCALE&WT_FILE_FORMAT=pdf&WT_ASSET=Documentation&fileExt=.pdf")

## Driver source for FEZ Hat
Product page: https://www.ghielectronics.com/catalog/product/500 
Source for drivers: https://bitbucket.org/ghi_elect/windows-iot
Schematic: http://www.ghielectronics.com/downloads/schematic/FEZ_HAT_SCH.pdf

### Motors (one of many):
https://www.pololu.com/product/1688
http://botland.com.pl/standard-micro-silniki-pololu/705-silnik-pololu-5-1.html


### Physical Connection:
1. Connect first motor to A (+, -), second to B (+, -). If you reverse polarity - nothing (wrong) will happen, just motor will react in opposite way.
2. Connect separate power source (can be 9V battery, or 4x1.5 battery pack etc) to Motor Power (connect +) and GND (connect -,  GND). 


## Other (similar) products: 
https://learn.adafruit.com/adafruit-tb6612-h-bridge-dc-stepper-motor-driver-breakout/overview
https://www.pololu.com/product/713
http://botland.com.pl/sterowniki-silnikow-moduly/32-tb6612-dwukanalowy-sterownik-silnikow-modul-pololu.html
http://botland.com.pl/sterowniki-silnikow-moduly/5459-explore-duonect-pca9685-generator-pwm-i2c-mod-71.html
...(use favorite search engine) 

#### Caution: you need to adopt source code of course!

