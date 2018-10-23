# Raspberry3B-433-Mhz-HIDEKI-sensors

Build up of a weather station made by a RaspberryPi mod. 3B, 433 Mhz HIDEKI sensors (HIDEKI TS21 for external temperature and 
humidity, TS805 for wind, TS906 for rain), BMP180 sensor for internal temperature and pressure, RTL dongle NooElec R820T SDR,
using Domoticz software.

SOFTWARE
- Raspbian Stretch Lite (https://www.raspberrypi.org/downloads/raspbian/)
- rtl-sdr (https://gist.github.com/floehopper/99a0c8931f9d779b0998)
- rtl_433 (https://github.com/merbanan/rtl_433)
- Domoticz (https://www.domoticz.com)

HARDWARE
- RTL-SDR dongle NooElec R820
- home made antenna (a long wire) for 4 m range through one wall
- wireless (433 MHz) HIDEKI sensor TS21 for temperature and humidity
- wireless (433 MHz) HIDEKI sensor TS805 for wind and temperature
- wireless (433 MHz) HIDEKI sensor TS906 for rain
- BMP180 sensor for temperature and pressure

Parameters for rtl_433 : -p 61 -R 42

-p 61 = correction for rtl-sdr tuner frequency offset error (determined with rtl_test -p)
-R 42 = HIDEKI TS04 Temperature, Humidity, Wind and Rain Sensor



