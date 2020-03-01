![Actions Status](https://github.com/zeoneo/master-build/workflows/pio-esp-ili9486/badge.svg)


#   About this project

I am simply trying to using any command line tool to build embedded project because I am tired of IDEs like Arduino. It was easy in the days of MAKE.

In this task I will be writing some platform io library to connect to SPI display (esp8266_ILI9486)

Graphics Driver.


## First time set up.

1. Install platformio cli. In general follow this [link](https://docs.platformio.org/en/latest/installation.html)

    On Mac
    
    `brew install platformio`

2. To build the project execute
    
    `pio run`

3. To upload the project use following command

    `pio run -t upload --upload-port your port name`

    Sample Command

    `pio run -t upload --upload-port /dev/cu.SLAB_USBtoUART`
