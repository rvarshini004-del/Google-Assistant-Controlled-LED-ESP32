# Google Assistant Controlled LED Lamp Using ESP32

## Project Overview
This project is designed to control an LED lamp using voice commands through Google Assistant. It uses an ESP32 microcontroller, a relay module, Wi-Fi connectivity, and the Sinric Pro IoT cloud platform.

## Objectives
- To control an LED lamp using voice commands.
- To connect ESP32 with the internet through Wi-Fi.
- To use Sinric Pro as an IoT cloud platform.
- To develop a simple smart home automation system.

## Components Required

### Hardware
- ESP32 Development Board
- Relay Module
- LED Lamp
- Power Supply
- Connecting Wires
- Breadboard

### Software
- Arduino IDE
- Sinric Pro Platform
- Google Assistant
- Wi-Fi
- Required Arduino Libraries

## Working Principle
1. The user gives a voice command through Google Assistant.
2. The command is processed through the Sinric Pro cloud platform.
3. Sinric Pro communicates with the ESP32 through Wi-Fi.
4. The ESP32 receives the control command.
5. The ESP32 controls the relay module.
6. The relay switches the LED lamp ON or OFF based on the command.

## Block Diagram

Google Assistant  
       ↓  
Sinric Pro Cloud  
       ↓  
Wi-Fi Communication  
       ↓  
ESP32 Controller  
       ↓  
Relay Module  
       ↓  
LED Lamp

## Libraries Used
- WiFi
- ArduinoJson
- SinricPro
- SinricProSwitch

## Applications
- Smart Home Automation
- Voice-Controlled Lighting
- IoT-Based Lighting Systems
- Remote Lamp Control

## Advantages
- Easy voice-based operation.
- Low-cost automation system.
- Wireless control using Wi-Fi.
- Convenient lighting management.

## Conclusion
The project successfully demonstrates a voice-controlled LED lamp using ESP32 and Google Assistant. The Sinric Pro cloud platform enables communication between Google Assistant and ESP32, making it a simple IoT-based smart home automation system.
