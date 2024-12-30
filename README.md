# 📱 Arduino Bluetooth Communication App

This repository contains the source code for an **Android application** developed to communicate with the Arduino Bluetooth Module **HC-05**. The application was part of a **hardware lab project** and has been customized from existing code to suit specific project requirements.

---

## 🛠️ Project Overview

### 🧩 **Purpose**:
- The application receives a **4-digit binary number** transmitted from an Arduino device via the **HC-05 Bluetooth Module**.
- The binary number is calculated using **flex sensors** based on the user’s finger movements.
- Upon receiving the binary number, the app matches it to a predefined dictionary of numbers and texts.
- The application **reads out the associated text** using text-to-speech functionality.

### ⚙️ **How It Works**:
1. **Flex Sensor Input**: The user's finger movements are captured using flex sensors connected to Arduino.
2. **Binary Conversion**: The Arduino calculates a 4-digit binary number based on the input.
3. **Bluetooth Transmission**: The binary number is transmitted to the Android app via the HC-05 Bluetooth module.
4. **App Processing**:
   - Receives the binary number.
   - Matches it to a predefined text in its dictionary.
   - Reads out the corresponding text aloud using the phone's speaker.

---

## 🚀 Features

- **Bluetooth Communication**: Connects seamlessly to HC-05 Bluetooth Module.
- **Binary-to-Text Mapping**: Predefined dictionary for quick lookups.
- **Text-to-Speech**: Reads out predefined text based on the received binary number.
- **User-Friendly Interface**: Simple design for easy interaction.

---

## 🛠️ Technologies Used

- **Android Studio**: Development environment.
- **Java**: Core programming language.
- **HC-05 Bluetooth Module**: For communication between Arduino and the Android device.
- **Arduino**: For processing input from flex sensors.
- **Text-to-Speech API**: Converts matched text to audio output.

---

