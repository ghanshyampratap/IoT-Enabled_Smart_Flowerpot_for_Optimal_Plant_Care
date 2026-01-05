# Smart Flowerpot 

## Overview 

The **Smart Flowerpot** is an IoT-based project designed to monitor soil moisture, temperature, and humidity. Powered by an ESP8266 module, it displays real-time data on an LCD and a web interface, and gives visual alerts using LEDs. This system helps ensure your plants stay healthy and well-watered! 

## Features 

- **Soil Moisture Monitoring**   
  Measures soil moisture and indicates the level using four LEDs:
  - **Red LED**: Very dry soil (Moisture < 30%) 
  - **Yellow LED**: Medium moisture (30% ≤ Moisture < 60%) 
  - **White LED**: High moisture (60% ≤ Moisture < 80%) 
  - **Blue LED**: Saturated soil (Moisture ≥ 80%) 

- **Temperature & Humidity Monitoring** 
  Uses a DHT11 sensor to monitor ambient conditions and displays readings.

- **LCD Display** 
  Shows real-time moisture %, temperature, humidity, and mood face.
  
 ![image](https://github.com/user-attachments/assets/3fcb67f4-ddfb-4afe-a35a-dd941c7bade9)
 
![image](https://github.com/user-attachments/assets/0d411e32-be47-4f78-8ce4-4aebcbd8659e)

- **Web Interface**   
  Access data remotely through a hosted web server with auto-refresh every 5 seconds.
  
![image](https://github.com/user-attachments/assets/f0c399e0-48ea-4c83-b8b5-69965bff362a)
## Components Used 🛠️

- **ESP8266 Wi-Fi Module**   
- **DHT11 Temperature and Humidity Sensor**  
- **Soil Moisture Sensor**   
- **LEDs** (Red, Yellow, White, Blue) 
- **16x2 LCD with I2C Interface** 
- **Jumper Wires**   

## Web Interface 

The ESP8266 hosts a web page that displays:
-  **Soil Moisture** (%)
-  **Temperature** (°C)
-  **Humidity** (%)
- 😀 **Mood** based on soil condition

Auto-refresh updates data every 5 seconds.

## Application Use Cases 

- **Home Gardening**  
- **Agriculture Monitoring**  
- **Smart Irrigation Systems**  
- **Educational IoT Projects** 

## Setup Instructions 

1. Clone or download this project.
2. Open the code in Arduino IDE.
3. Install required libraries:
   - `LiquidCrystal_I2C`
   - `ESP8266WiFi`
   - `ESP8266WebServer`
   - `DHT`
4. Replace the `ssid` and `password` in code with your Wi-Fi credentials.
5. Upload the code to your ESP8266.
6. Open Serial Monitor to find the IP address.
7. Access the web page using that IP on your browser.
8. Watch the LCD and LED indicators for real-time feedback.

   ![image](https://github.com/user-attachments/assets/7c1d0b86-80c4-4bde-a29f-3513b34b42d5)


## Conclusion 

The **Smart Flowerpot** makes plant care easier and smarter. From real-time sensing to web-based monitoring, it's perfect for automation, learning, and keeping your greens happy! 🍀🌼

---

**Happy Gardening!** 
