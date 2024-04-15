# Android-controlled-car
This project is a DIY Android-controlled car built using an ESP32-CAM module and an L298N motor driver. With this setup, you can control the movements of the car using a simple Android application.

# Table of Contents
 Demo
 Features
Hardware Requirements
Software Requirements
Installation


# Features
Android Control: Use a custom Android app to wirelessly control the car.
Live Video Streaming: Stream live video from the ESP32-CAM to your phone.
Customizable: Modify the Arduino code and Android app to suit your needs.
Simple Interface: Easy-to-use Android interface for intuitive control.
Hardware Requirements
To build this project, you will need the following hardware components:

ESP32-CAM Module
L298N Motor Driver
DC Motors (2x)
Motor Wheels (2x)
Chassis for the Car
18650 Batteries (2x) and Holder
Jumper Wires
Breadboard
Android Smartphone/Tablet
Software Requirements
Arduino IDE
Android Studio
Installation
Setting Up ESP32-CAM
Clone or download this repository.
Open the esp32_cam_control.ino file in Arduino IDE.
Install the required libraries (mention libraries if any).
Configure the SSID and Password of your Wi-Fi network in the code.
Upload the code to your ESP32-CAM module.
Setting Up Android App
Open the android_app folder in Android Studio.
Customize the app as needed (change colors, layout, etc.).
Build and install the APK on your Android device.
Usage
Power on the ESP32-CAM car and connect to its Wi-Fi network.
Open the Android app on your device.
Connect to the ESP32-CAM Wi-Fi network from the app.
Start controlling the car using the on-screen buttons.
Enjoy the live video stream from the ESP32-CAM.
Contributing 
