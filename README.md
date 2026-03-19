# Motion Sensor Light using IR Proximity Sensor & CD4017 IC

<div align="center">

![Status](https://img.shields.io/badge/Status-Completed-success)

> **An automatic motion-activated lighting system using digital logic circuits**

[The British University in Egypt](https://www.bue.edu.eg/) | Faculty of Informatics & Computer Science  
**Module:** Electronics and Digital Circuits (`25CSCI10C`) | **Year:** 1 (Post-Preparatory)

</div>

## 👥 Team Members

### Team A14T4

| Student ID | Name | Email |
|:----------:|------|-------|
| 257678 | Mahmoud Samir Moustafa | mahmoud257678@bue.edu.eg |
| 251551 | Youssef Wael Fawzy | youssef251551@bue.edu.eg |
| 257403 | Ziad Mostafa Gaber | ziad257403@bue.edu.eg |
| 258948 | Ziad Ayman | ziad258948@bue.edu.eg |
| 244144 | Ahmed Ali Abdelmotjal | ahmed244144@bue.edu.eg |

---

## 📌 Project Overview

This project implements an **automatic motion sensor light** that detects movement using an IR (Infrared) proximity sensor and controls a lighting system through digital logic circuits. The design utilizes the **CD4017 decade counter IC** as the main control unit, eliminating the need for microcontrollers or programming.

### Key Highlights
- 🔍 **Contactless Detection:** Uses IR technology to detect motion/obstacles
- 🎛️ **Pure Hardware Solution:** No programming or microcontroller required
- ⚡ **Relay-Based Control:** Can switch AC/DC loads safely
- 💡 **Energy Efficient:** Automatic on/off based on motion detection
-  **Educational Value:** Demonstrates fundamental digital electronics concepts

---

## ✨ Features

| Feature | Description |
|---------|-------------|
| **Motion Detection** | IR sensor detects objects within 2-30 cm range |
| **Automatic Control** | Light turns ON when motion detected, OFF when clear |
| **Visual Indicators** | Red LED (standby) and Green LED (active) status |
| **Load Control** | 9V relay controls 6V lamp or other compatible loads |
| **Low Power** | Operates on 9V battery for portability |
| **No Coding** | Pure hardware implementation using logic ICs |

---

## 🔧 Components Required

### Main Components

| Component | Quantity | Specification | Purpose |
|-----------|----------|---------------|---------|
| IR Obstacle Sensor | 1 | HC-SR501 or similar | Motion detection |
| CD4017 IC | 1 | Decade Counter | Logic control |
| BC557 Transistor | 1 | PNP | Signal switching |
| BC547 Transistor | 1 | NPN | Relay driver |
| Relay | 1 | 9V SPDT | Load switching |
| LED (Red) | 1 | 5mm | Status indicator |
| LED (Green) | 1 | 5mm | Status indicator |
| Diode | 1 | 1N4007 | Flyback protection |

### Passive Components

| Component | Value | Quantity |
|-----------|-------|----------|
| Resistor | 10kΩ | 1 |
| Resistor | 4.7kΩ | 1 |
| Resistor | 220Ω | 3 |
| Capacitor | 100nF | 2 |
| Capacitor | 1pF | 1 |

### Power & Load

| Component | Specification |
|-----------|---------------|
| Power Supply | 9V Battery |
| Load | 6V Lamp/Bulb |

---

## 📐 Circuit Diagram

<div align="center">

![Circuit Diagram](Project%20Schematic%20Diagram.jpg)

*Figure 1: Complete circuit schematic showing IR sensor, CD4017 IC, and relay control*

</div>

### Circuit Sections

1. **Sensor Module:** IR transmitter/receiver pair
2. **Control Logic:** CD4017 decade counter with clock input
3. **Driver Stage:** BC557/BC547 transistor configuration
4. **Output Stage:** Relay with flyback diode protection
5. **Power Supply:** 9V regulated supply with decoupling capacitors

---
