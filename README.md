# 🌡️ IoT Temperature & Humidity Monitor (ESP32)

## Overview
This project measures temperature and humidity using a DHT11 sensor and an ESP32.  
The sensor data is displayed in the Serial Monitor.

## Components
- ESP32 Development Board
- DHT11 Sensor
- Breadboard
- Jumper Wires

## Connections

| DHT11 | ESP32 |
|------|------|
| VCC | 3.3V |
| GND | GND |
| DATA | GPIO21 |

## Output
The ESP32 reads the temperature and humidity values and prints them in the Serial Monitor.

Example output:
Temperature: 28°C  
Humidity: 60%

## Applications
- Weather monitoring
- Smart home monitoring
- IoT environmental sensing
