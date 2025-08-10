ESP32 Heater Control System (DHT22)
A simple heater control system using an ESP32 and DHT22 sensor.
Controls a heater based on temperature thresholds and triggers LED and buzzer alerts on overheat.

Features

Reads temperature and humidity from DHT22
Implements five states: Idle, Heating, Stabilizing, Target Reached, Overheat
Automatic heater control with hysteresis
LED and buzzer alert during overheat
Serial logging of temperature, humidity, and state

Hardware & Pins

DHT22 data : GPIO 21
Heater control : GPIO 25
Status LED : GPIO 2
Buzzer : GPIO 26

Temperature Thresholds

Target temperature: 28 Deg C
Hysteresis: +or- 0.5 Deg C
Overheat temperature: 32 Deg C
