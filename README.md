# My_NTP_ESP32_Morphing_Clock

This Clock is a remix from [HariFun_166_Morphing_Clock ](https://github.com/hwiguna/HariFun_166_Morphing_Clock/tree/master) with some modifications, Including easy WiFi setup and a Website control to change the settings. Still a work in progress.

![Animated image showing Morphing Clock](/images/myClock.gif)

## Inspiration from the following sources:

WebSite Page based on: [dragondaud/myClock](https://github.com/dragondaud/myClock)

WiFi Setting and ArduinoJson: [witnessmenow](https://github.com/witnessmenow/ESP32-Trinity)

Website's clock from: [3tawi](https://github.com/3tawi/P4-Matrix-64x32-Esp32-DHT22-DHT11-RTC-DS1307-SD-CARD)

How to create this page: [Tutorial](https://github.com/witnessmenow/ESP-Web-Tools-Tutorial)

Web Flash Page: [WLED-WebInstaller](https://github.com/Aircoookie/WLED-WebInstaller) 

## Libraries used:

Arduino IDE 1.8.19: [Arduino IDE 1.8.19](https://www.arduino.cc/en/software)

HUB75 Matrix: [mrfaptastic/ESP32-HUB75-MatrixPanel-DMA](https://github.com/mrfaptastic/ESP32-HUB75-MatrixPanel-DMA)

WiFiManager: [tzapu/WiFiManager](https://github.com/tzapu/WiFiManager)

ezTime Library: [ropg/ezTime](https://github.com/ropg/ezTime)

ArduinoJson: [bblanchon/ArduinoJson 6.21.2](https://github.com/bblanchon/ArduinoJson)

Adafruit GFX: [Adafruit-GFX](https://github.com/adafruit/Adafruit-GFX-Library) and all of it's dependancy libraries.

Lookup TimeZone from IP using: http://ip-api.com/ (no API key required).

Get current weather data from https://openweathermap.org/api which requires an API key to use.

## Compatible Development Boards:

I'm working on my Own ESP32 Shield or Development Board, but the following are compatible with this project.

ESP32-Trinity from witnessmenow: [ESP32-Trinity](https://github.com/witnessmenow/ESP32-Trinity)

Electrodragon Board: [Interface Board for ESP32 DMA](https://www.electrodragon.com/product/rgb-matrix-panel-drive-interface-board-for-esp32-dma/)

## Web Flash Link

;;;;[Web Flash Link](https://wilson3682.github.io/My_NTP_ESP32_Morphing_Clock/flash.html)

[Web Flash WLED Style](https://wilson3682.github.io/My_NTP_ESP32_Morphing_Clock/install.html)

### After flashing

Once installed, it will create a WiFi access point called:

#### SSID: NTP MORPHING Clock

#### pass: 123456789

Connect to the NTPMorphingClock Access Point and enter the password, then connect it to your personal WiFi.

## Web Page Access

Once connected, access the Webpage with the new ip address and the following credentials, to have access to the clocks's settings.

###  Web access credentials:
#### username: admin
#### pass: 123456789

#### WebPage. ![WebPage](/images/mainpage.png)

## Clock Modes

#### Blinking Colon version. 
![BlinkingColon](/images/BlinkingColon.gif)

#### New Version. Smaller second digits and showing AM or PM 
![BlinkingColonNew](/images/BlinkingColonNew.gif)

## 
