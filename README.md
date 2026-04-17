# 🤖 Mochi Desk Companion  

![GitHub repo size](https://img.shields.io/github/repo-size/your-username/mochi-desk-companion)
![GitHub stars](https://img.shields.io/github/stars/your-username/mochi-desk-companion?style=social)
![GitHub forks](https://img.shields.io/github/forks/your-username/mochi-desk-companion?style=social)
![License](https://img.shields.io/badge/license-MIT-green)

> ✨ An interactive ESP32-based desk robot with personality, animations, and IoT connectivity.

---

## 🎥 Demo Preview

<p align="center">
  <img src="docs/demo.gif" alt="Mochi Demo" width="250"/>
</p>

> 📌 *Add your GIF inside `/docs/demo.gif`*

---

## 📸 Project Preview

<p align="center">
  <img src="docs/mochi1.jpg" width="200"/>
  <img src="docs/mochi2.jpg" width="200"/>
</p>

---

## 📌 Overview

Mochi is a compact **ESP32-C3 powered IoT desk companion** that displays animated expressions, reacts to touch, plays sounds, and syncs with your phone via Bluetooth.

Designed for **students, makers, and embedded engineers**, it combines hardware + software into a fun interactive device.

---

## ✨ Features

- 🎭 80+ expressive OLED animations  
- 🔊 Smart audio alerts via buzzer  
- 📱 BLE mobile connectivity  
- 👆 Touch-based interaction  
- 🌐 Web-based firmware flashing  
- ⚡ Real-time notifications & syncing  

---

## 🧠 System Architecture

```text
Mobile App (BLE)
        ↓
   ESP32-C3 MCU
        ↓
 OLED Display + Buzzer
