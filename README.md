Weater forecasts station on your NodeMCU!

Parts:
- NodeMCU 1.0
- Oled display 128x64
- battery
- wires

How it works?
Well, the ESP8266 connects automatically to your wunderground account (visit www.wunderground.com and get a free account).
Automatically connects to you wify, downloads data (json file) and gets forecasts for the current day, then displays it on screen.
The main problem was setting wifi connection AND initializing the oled display. I couldn't do it, because of a lot of different libraries around, the new Arduino IDE had some troubles and other things.
So i decided to connect to wifi, download data and then get everything ok with the Oled display.
I got so many errors that i let it this way...
But i'll fix it somehow, and i'll publish the finished code with all the errors that i've been trough.
