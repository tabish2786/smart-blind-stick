# Smart Blind Stick

A smart walking stick to help visually impaired people detect obstacles safely.

## Description
This project uses an ultrasonic sensor to detect obstacles. When something is close:
- Buzzer beeps (faster when closer)
- Servo motor sweeps left-right to scan a wider area

## Components
- Arduino Uno
- HC-SR04 Ultrasonic Sensor
- Buzzer
- SG90 Servo Motor
- Jumper wires & breadboard

## Connections
- Ultrasonic Sensor:
  - VCC → 5V
  - GND → GND
  - Trig → Pin 9
  - Echo → Pin 10
- Servo Motor:
  - Red → 5V
  - Brown → GND
  - Orange → Pin 6
- Buzzer:
  - + → Pin 7
  - – → GND

## Features
- Obstacle detection up to ~300 cm
- Variable buzzer alert (faster = closer)
- Servo scanning when obstacle detected
- Serial monitor shows distance

## How to Use
1. Upload the code to Arduino
2. Connect components
3. Power on and walk — it will alert you!

Made with ❤️ by Tabish2786
