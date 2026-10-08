# 🤖 Wireless Voice Controlled Robot Car

ESP8266 + L298N based IoT Robot controlled wirelessly via Voice Commands from Android App. Base platform for Humanoid Robot.

### Built by Nanditha M | Dept of DS & AI

## 📱 How it Works (Simple)
1. Robot creates WiFi hotspot "Archana"
2. Phone connects to it
3. User says "Forward" on app -> App sends "F" to robot
4. Robot moves forward, backward, left, right, diagonal + speed control + stop

## 🔧 Hardware Used
- NodeMCU ESP8266
- L298N Motor Driver
- DC Motors x 4
- Battery 12V
- Chassis

## Pin Map
- ENA 14 (D5), ENB 12 (D6)
- IN_1 15 (D8), IN_2 13 (D7)
- IN_3 2 (D4), IN_4 0 (D3)

## Commands
- F=Forward, B=Back, L=Left, R=Right, G=ForwardLeft, I=ForwardRight, H=BackLeft, J=BackRight, S=Stop, 0-9=Speed

## Fixed Issue
Added missing HTTP_handleRoot() function - now compiles 100% without error.

## Future Scope
Add 6x MG995 Servo motors for hands/legs to make full humanoid, Add camera + ChatGPT brain.
