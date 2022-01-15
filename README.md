# AHT10_Tasmota_10.1
https://tasmota.github.io/docs/AHT1x/#tasmota-settings
https://tasmota.github.io/docs/Compile-your-build/#compiling-tools
https://github.com/benzino77/tasmocompiler
https://benzino77-tasmocompiler-uxxngykffxi.ws-eu27.gitpod.io/
https://crashdown.de/2020/05/01/wemos-d1-mini-on-tasmota-with-aht10-sensor/

3.Select features
Temp/Hum sensors

4.Custom parameters

#ifndef USE_AHT1x
#define USE_AHT1x       // [I2cDriver43] Enable AHT10/15 humidity and temperature sensor (I2C address 0x38) (+0k8 code)
#endif

SONOFF BASIC R2
 
Configuration - Configure Other - Template 

{"Time":"2020-01-01T00:00:00","AHT1X-0x38":{"Temperature":24.7,"Humidity":61.9,"DewPoint":16.8},"TempUnit":"C"}

Activate

Configure module

TX GPIO1 - I2C SCL
RX GPIO3 - I2C SDA
