NEU Wireless RFID Attendance Project
=====================================
NEU Wireless club project for creating a Husky Card RFID attendance system using the PN532 
NFC reader. Requires:
1. Raspberry PI
2. NXP PN532 chip (Configured for SPI communication)

## Pinouts

You can easily match the PN532 pins to the SPI pins on the GPIO headers:

| Chip Pin | Raspi Pin |
| -------- | --------- |
| SCK      | GPIO 11 (SCLK)|
| MISO     | GPIO 9  |
| MOSI     | GPIO 10 |
| SS       | GPIO 8 (CE0) |
| VCC/GND  | Aren't you an EE? |

## Installation
```
sudo apt-get update
sudo apt-get install build-essential python-dev git
cd Adafruit_Python_PN532
sudo python setup.py install
```
