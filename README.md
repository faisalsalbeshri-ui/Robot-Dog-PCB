# 🐕 Robot Dog PCB

![PCB](https://img.shields.io/badge/PCB-Double%20Layer-blue)
![Arduino](https://img.shields.io/badge/Controller-Arduino%20Nano-00979D)
![EasyEDA](https://img.shields.io/badge/Designed%20with-EasyEDA-1765F6)
![Status](https://img.shields.io/badge/Status-Completed-success)

## 📌 Project Overview

This project presents a custom **Double-Layer PCB** designed for a robotic dog control system.

The PCB was designed using **EasyEDA** and is based on an **Arduino Nano** as the main controller. It provides dedicated connections for four servo motors, an ultrasonic sensor, and an external battery supply.

The board was designed with organized component placement, clearly labeled connectors, and routing across both the top and bottom copper layers.

---

## 🎯 Task Requirements

The PCB was designed to satisfy the required specifications:

- Arduino Nano or ESP32 as the main controller
- Four servo motor connectors
- Battery connection
- Sensor connection
- Logical and organized component placement
- Clear labeling for all connectors
- Double-Layer PCB design

All required elements were implemented in the final design.

---

## 🔧 Hardware Components

| Component | Quantity | Purpose |
|---|---:|---|
| Arduino Nano | 1 | Main controller |
| Servo Connectors | 4 | Connections for robotic dog servo motors |
| Ultrasonic Sensor Connector | 1 | Distance sensing |
| Battery Terminal | 1 | External power input |
| PCB | 1 | Double-layer control board |

---

## 🔌 PCB Interfaces

The board includes clearly labeled interfaces for:

- `SERVO1`
- `SERVO2`
- `SERVO3`
- `SERVO4`
- `BATTERY`
- `ULTRASONIC`

This makes the PCB easier to assemble, connect, test, and maintain.

---

## 🧠 Main Controller

The **Arduino Nano** is used as the main processing unit of the PCB.

It provides the required digital I/O and power connections for controlling the servo interfaces and communicating with the ultrasonic sensor.

---

## 📡 Ultrasonic Sensor

An ultrasonic sensor interface was included as the additional sensor required by the task.

It can be used by the robotic dog for applications such as:

- Obstacle detection
- Distance measurement
- Basic autonomous navigation

---

## ⚡ Power Connection

A dedicated **BATTERY** terminal is included on the PCB to provide an external power connection to the robotic dog control system.

The connector is clearly labeled on the PCB for easier identification during assembly.

---

## 🐾 Servo Motor Connections

Four dedicated 3-pin connectors are included for the robotic dog's servo motors:

| Connector | Function |
|---|---|
| SERVO1 | Servo Motor 1 |
| SERVO2 | Servo Motor 2 |
| SERVO3 | Servo Motor 3 |
| SERVO4 | Servo Motor 4 |

Each servo interface provides the required signal and power connections.

---

## 🧩 Schematic Design

The schematic was created first to define the electrical connections between:

- Arduino Nano
- Four servo connectors
- Battery connector
- Ultrasonic sensor connector

### Schematic

![Robot Dog PCB Schematic](Robot-Dog-PCB-Schematic.png)

---

## 🛠️ PCB Layout

After completing the schematic, the circuit was converted into a PCB layout.

The components were arranged logically to keep the design organized and make routing easier.

The routing uses both copper layers:

- 🔴 **Top Layer**
- 🔵 **Bottom Layer**

This allows traces to cross safely using different PCB layers while maintaining the required **Double-Layer PCB** design.

### 2D PCB Layout

![Robot Dog PCB 2D Layout](Robot-Dog-PCB-2D-Layout.png)

---

## 🖥️ 3D PCB View

The final PCB was also inspected using the EasyEDA 3D Viewer.

The 3D model provides a realistic preview of the final board, including the Arduino Nano, battery terminal, sensor connector, and servo connectors.

### Final 3D Design

![Robot Dog PCB 3D View](Robot-Dog-PCB-3D-View.png)

---

## ✅ Design Verification

The completed PCB was checked using the **Design Rule Check (DRC)** tool in EasyEDA.

### Final Check

- Component placement completed
- All required connectors included
- All connectors labeled
- Top Layer routing completed
- Bottom Layer routing completed
- Double-Layer PCB implemented
- PCB boundary completed
- 3D model inspected
- DRC completed with **0 errors**

---

## 🔄 Design Workflow

The project was completed using the following workflow:

1. Define the PCB requirements
2. Select the Arduino Nano as the controller
3. Add four servo connectors
4. Add the battery connector
5. Add the ultrasonic sensor connector
6. Create the circuit schematic
7. Connect the required signals and power lines
8. Convert the schematic to PCB
9. Arrange the components inside the board boundary
10. Route the traces using the Top and Bottom layers
11. Add clear connector labels
12. Run Design Rule Check (DRC)
13. Verify that no DRC errors remain
14. Inspect the final PCB using the 3D Viewer
15. Save the completed design

---

## ✨ Key Features

- Custom robotic dog PCB
- Arduino Nano based design
- Four independent servo interfaces
- Ultrasonic sensor interface
- Dedicated battery input
- Clearly labeled connectors
- Organized component placement
- Double-layer trace routing
- DRC verified
- 3D PCB visualization

---

## 🛠️ Software & Tools

### EasyEDA

The schematic, PCB layout, routing, labeling, DRC verification, and 3D visualization were completed using **EasyEDA**.

🔗 [EasyEDA](https://easyeda.com/)

### GitHub

GitHub is used to document and share the final project files and design results.

🔗 [GitHub](https://github.com/)

---

## 📂 Project Files

```text
Robot-Dog-PCB/
│
├── README.md
├── Robot-Dog-PCB-Schematic.png
├── Robot-Dog-PCB-2D-Layout.png
└── Robot-Dog-PCB-3D-View.png
```

---

## 📸 Project Results

The repository documents the complete PCB development process through three main views:

1. **Schematic Design** – electrical connections and components
2. **2D PCB Layout** – component placement and double-layer routing
3. **3D PCB View** – final physical board visualization

---

## 🚀 Future Improvements

Possible future improvements include:

- Adding mounting holes
- Adding additional sensors
- Improving power distribution
- Adding protection components
- Optimizing PCB dimensions
- Integrating additional robotic dog control features

---

## 👤 Author

**Faisal Albeshri**

Computer Engineering Student

---

## 📄 Project Status

**Completed ✅**

The final PCB satisfies the required robotic dog PCB specifications and was successfully designed and verified using EasyEDA.
