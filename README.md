# Flash-ADC-project
Design and implementation of flash ADC using parallel comparators and encoders in Cadence Virtuoso 
# 🚀 3-Bit Flash ADC Design Using Cadence Virtuoso

This repository contains the complete design and implementation of a **3-bit Flash Analog-to-Digital Converter (ADC)** using **Cadence Virtuoso (gpdk90nm technology)**. A Flash ADC is the fastest type of ADC, capable of generating output in *a single clock cycle* using parallel comparators.

---

## 🔍 Abstract

This project presents the schematic design, working principle, performance analysis and simulation results of a **3-bit Flash ADC**.  
The ADC consists of:
- Resistor ladder reference network
- 7 parallel comparators (thermometer output)
- Thermometer-to-Binary encoder
- Designed and simulated in Cadence Virtuoso

Flash ADC architecture enables extremely fast conversion and is used in real-time systems such as RADAR, communication receivers, oscilloscopes etc.

---

## 📁 Repository Content

| File | Description |
|------|-------------|
| 📄 `final_report_minio2.pdf` | Complete project report with design + waveform results |
| 📝 `README.md` | Project documentation (this file) |

You may later add:
- `/schematics` → circuit screenshots
- `/waveforms` → simulation output images
- `/encoder` or `/ladder` images

---

## 🏗 Architecture Blocks

1. **Sample & Hold** — captures analog input
2. **Resistor Ladder** — generates reference voltages
3. **Comparator Array (7 comparators)** — produces thermometer code
4. **Encoder** — converts thermometer → 3-bit binary

All blocks were built and simulated using **Cadence Virtuoso + Spectre**.

---

## 📊 Performance Summary

| Parameter | Value |
|----------|-------|
| Technology | 90nm (gpdk) |
| Resolution | 3-bit |
| Vdd | 1.2V |
| Input Voltage | 0 – 1.2V |
| Power Dissipation | ~3.68mW |
| Delay | ~363.7µs |

---

## 📄 View Full Report

👉 Click to open PDF:  
**[Flash ADC Project Report](./final_report_minio2.pdf)**

---

