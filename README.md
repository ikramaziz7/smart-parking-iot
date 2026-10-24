# Smart Parking IoT — ParkGo

> IoT mini-project — Université Hassan 1er, Faculté des Sciences et Techniques Settat (2023–2024)  
> **Team**: Hanane Mazyan, Chaymae Moudnib, **Ikram Aziz**, Marwa Jaida, Wissal Hidaoui  
> **Supervisor**: Prof. Karim Tahiry

## Overview

**ParkGo** (*"Your Smart Spot"*) is an IoT-based smart parking system designed to address urban mobility challenges. The project provides real-time monitoring of parking availability, guiding motorists to vacant spaces with pinpoint accuracy through an integrated IoT platform and web dashboard.

The project was motivated by Morocco's preparation for major sporting events (Africa Cup of Nations, FIFA World Cup), which were expected to bring significant traffic surges to cities like Casablanca.

## Problem Statement

Urban parking inefficiency leads to:
- Increased traffic congestion and CO₂ emissions
- Wasted time for drivers searching for spots
- Economic losses for parking operators

**ParkGo** addresses this by deploying IoT sensors to detect occupancy in real time and exposing the data through a web interface and decision-support dashboard.

## System Architecture

### Hardware Components

| Component | Role |
|-----------|------|
| Ultrasonic / IR sensors | Detect vehicle presence per parking spot |
| Arduino microcontrollers | Collect sensor data at parking level |
| ESP8266 / Wi-Fi module | Transmit data to the cloud |
| LED indicators | Local visual feedback per spot |

### Software Stack

| Component | Technology |
|-----------|-----------|
| Firmware | Arduino IDE (C/C++) |
| Backend | IoT platform / MQTT broker |
| Frontend | Web dashboard (HTML/CSS/JS) |
| Data pipeline | Data collection → visualisation → decision support |

## Key Features

- **Real-time occupancy monitoring** — sensors poll every few seconds
- **Data visualisation** — live dashboard showing free/occupied spots on a map
- **Data-driven decision making** — historical analytics to optimise parking allocation
- **Impact analysis** — evaluation of ParkGo's effect on traffic flow and user experience

## Project Structure

```
smart-parking-iot/
├── iotrpt.pdf        # Full 46-page project report
└── README.md
```

## Report Contents

The full report covers:
1. Introduction — why smart parking?
2. Data collection and visualisation
3. Understanding ParkGo's impact
4. Data-driven decision making
5. Chapter 1: Overview of Smart Parking
6. Chapter 2: Electronic components
7. Chapter 3: Computer tools & Arduino IDE & Website
8. Chapter 4: Component analysis & experimental results
9. Conclusion

📄 [`iotrpt.pdf`](./iotrpt.pdf) — Full 46-page project report.

## Academic Context

- **Programme**: Système d'Information et Transformation Digitale (LST)  
- **Institution**: Université Hassan 1er — Faculté des Sciences et Techniques Settat  
- **Department**: Génie Électrique & Génie Mécanique  
- **Academic Year**: 2023–2024  
- **Supervisor**: Prof. Karim Tahiry
