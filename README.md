# MrFrog

Mr Frog Frog Mister Misting System for MrFrog

Mists a Frog on a schedule and/or based on humidity

This project is built for an ESP32 for use in [Home Assistant](https://www.home-assistant.io/) with [ESPHome](https://esphome.io/)
The device connects to WiFi, connects and Home Assistant can display the sensor 
data and remotely trigger mists, and send notifications. 

Details: 
- The micro-controller is an ESP32
- The sensors are a pair of DHT22 temp/humidity sensors
- The screen is a SSD1306 128x64 i2c display
- The motor is stolen from an off the shelf Reptile Mister
- The device does not connect to the internet, only to a local network. 

Feel free to reach out to me with any questions
