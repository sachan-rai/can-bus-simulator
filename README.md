# Automotive CAN Bus Simulator 🚗📡

This project simulates automotive ECU traffic on a Controller Area Network (CAN Bus) using a microcontroller (STM32/ESP32/Arduino Due) and CAN transceiver modules. It was built as a resume project to demonstrate embedded systems design, real-time firmware, and CAN protocol handling.

---

## 🎯 Objectives

- Simulate 2–3 virtual ECUs (e.g. Engine, Braking, Cluster)
- Transmit realistic CAN frames (RPM, Speed, Brake Status)
- Support interactive driving scenarios (Idle, Braking, Cruising, Fault)
- Build PC-based CAN monitor (Python)
- Add error injection and fault simulation (stretch)

---

## 🔧 Tools & Technologies

- **MCU:** ESP32
- **Transceiver:** MCP2551
- **Bus Interface:** USB-CAN adapter
- **PC Software:** Python + python-can
- **IDE:** Arduino IDE
- **Version Control:** GitHub
