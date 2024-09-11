# 🔌 Logic Probe Project

**Designed and Developed by Gonzalo Patino**

---

## 📋 Project Overview

The **Logic Probe** project was created as part of the final project for the course ETEC 225 at Centennial College. A logic probe is an essential tool for testing and troubleshooting digital circuits. The aim of this project was to design and fabricate a low-cost, easy-to-use, and safe logic probe that meets all the requirements outlined in the project goals.

---

## 🛠️ Project Objectives

- **Inexpensive**: The logic probe is designed to be cost-effective.
- **User-friendly**: The device is handy, portable, and easy to operate.
- **Safe**: High standards of safety were maintained in the design, including neat soldering.
- **Functional**: The probe operates efficiently under various testing conditions.

---

## 🔧 Theory of Operation

The logic probe uses two operational amplifiers acting as comparators:

1. **High Voltage Comparator**: Detects high logic levels.
2. **Low Voltage Comparator**: Detects low logic levels.

When the probe is used on a circuit, it compares the input logic level between the comparators. Depending on the voltage, either the high-level or low-level LED lights up, providing a visual and audible indicator of the logic state.

---

## 📊 Experiments & Test Results

During testing, the logic probe met all functional requirements under breadboard conditions. Here are key results:

- **High Logic Threshold**: 2.17V
- **Low Logic Threshold**: 0.93V
- **Current Consumption**: 16.11mA
- **Buzzer Frequency**: 2.7 kHz

All soldering and component placement were verified, and the device performed well in user tests on different breadboards and microcontroller applications.

---

## 🖥️ System Design & Schematics

- **Working Schematic**: The schematic shows the operational amplifiers, voltage references, LEDs, and other key components used in the logic probe.  
![Schematic](path-to-working-schematic-image)

- **PCB Design**: The PCB layout ensures neat and safe soldering, with clear board outlines, copper bottom, and top silk screen layers.
![Board Outline](path-to-board-outline-image)
![Copper Bottom](path-to-copper-bottom-image)
![Silk Screen](path-to-silk-screen-image)

---

## 🛒 Bill of Materials (BOM)

The project uses common and inexpensive components, making it affordable for full-scale production. Here’s a summary of the parts used:

| Part               | Description                       | Quantity | Price per Unit |
|--------------------|-----------------------------------|----------|----------------|
| IC: LM358          | Dual Op-Amp                       | 1        | $0.64          |
| Transistor: 2N3903 | N-P-N General Purpose Transistor  | 1        | $0.64          |
| Diode: 1N4148      | General Purpose Diode             | 1        | $0.64          |
| LED                | Miniature 3mm (Green, Red)        | 2        | $0.64 each     |
| Resistors          | Various (1/8W)                    | 8        | $0.64 each     |
| Buzzer             | 350Hz, DC Transducer              | 1        | $0.64          |

_Total Cost: $8.32_

---

## 🔍 Future Recommendations

The logic probe has proven to be a reliable, low-cost device with a robust design. Based on the positive results, full-scale production of the device is recommended.

---



## 📬 Contact

For any inquiries, feel free to reach out:

- **Email**: gpatinoc92@gmail.com
- **LinkedIn**: [Gonzalo Patino](https://www.linkedin.com/in/gpatinoc/)
