# 💧 Automatic Water Level Controller using Arduino

An Embedded Systems project developed using **Arduino Uno** and simulated using the **Wokwi Simulator**. This project automatically monitors the water level in a storage tank using an **HC-SR04 Ultrasonic Sensor** and controls the water pump through a relay module to prevent water overflow and dry running.

---

## 📖 Project Overview

The Automatic Water Level Controller is designed to reduce manual effort in monitoring water tanks. The ultrasonic sensor continuously measures the water level, and the Arduino processes the data to automatically switch the water pump **ON** or **OFF** based on predefined water level thresholds.

A **16×2 LCD Display** shows the current water level, pump status, and operating mode in real time. The project supports both **Automatic** and **Manual** modes, making it suitable for learning automation and embedded system design.

---

## ✨ Features

- 💧 Automatic Water Level Monitoring
- ⚡ Automatic Pump ON/OFF Control
- 🔄 Automatic and Manual Operating Modes
- 📟 Real-time LCD Display
- 📏 HC-SR04 Ultrasonic Sensor Interfacing
- 🔌 Relay-Based Pump Control
- 🖥️ Wokwi Simulation Support
- 💻 Embedded C Programming

---

## 🛠️ Components Used

- Arduino Uno
- HC-SR04 Ultrasonic Sensor
- 16×2 LCD Display
- Relay Module
- Push Buttons
- LED
- Potentiometer
- Jumper Wires

---

## 💻 Software Used

- Arduino IDE
- Wokwi Simulator
- Embedded C

---

## ⚙️ Working Principle

1. The HC-SR04 Ultrasonic Sensor measures the distance between the sensor and the water surface.
2. Arduino calculates the current water level.
3. The LCD displays the water level and pump status.
4. In **Automatic Mode**, the pump turns ON when the water level is low and turns OFF when the tank becomes full.
5. In **Manual Mode**, the user can control the pump using push buttons.

---

## 📂 Project Structure

```
Automatic-Water-Level-Controller/
│
├── README.md
├── code/
│   └── Automatic_Water_Level_Controller.ino
├── images/
│   ├── Circuit_Diagram.png
│   ├── Simulation_Output.png
│   └── LCD_Output.png
├── docs/
│   └── Project_Report.pdf
└── components/
    └── Components_List.md
```

---

## 📸 Circuit Diagram

![Circuit Diagram](images/Circuit_Diagram.png)

---

## 📸 Simulation Output

![Simulation Output](images/Simulation_Output.png)

---

## 📸 LCD Output

![LCD Output](images/LCD_Output.png)

---

## 📚 Learning Outcomes

Through this project, I gained practical experience in:

- Arduino Programming
- Embedded C
- Sensor Interfacing
- LCD Interfacing
- Relay Control
- Automation Logic
- Real-Time Monitoring Systems
- Embedded System Design

---

## 🚀 Future Improvements

- ESP32 Wi-Fi Integration
- IoT Dashboard
- Mobile App Monitoring
- Cloud Data Logging
- PCB Design
- Hardware Implementation

---

## 🔗 Project Links

### 🌐 Wokwi Simulation
https://wokwi.com/projects/467643897420931073

## 👨‍💻 Author

**Soumya Yadav**

B.Tech Electronics Engineering Student

**Interested in:**
- Embedded Systems
- Arduino
- ESP32
- IoT
- VLSI
  
