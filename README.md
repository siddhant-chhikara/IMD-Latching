# ⚡ IMD Latch PCB – High Voltage Safety Interface for Formula Student EV

This repository contains the complete design for a **custom fault detecting PCB** developed for a Formula Student electric vehicle (DR'25).

# 🔧 Project Overview

The PCB takes input signal from the **Insulation Monitoring Device (IMD)** of the EV (IMD checks for galvanic isolation between two independent circuitries incase of any fault or any current leaks bw both isolated circuits the IMD sends a fault signal) and performs critical safety operations:

- Latches fault signals and triggers a shutdown in case of insulation failure
- Drives cockpit indicator lights to inform the driver of system state
- Implements logic to foolproof shutdown behavior in edge cases
- Includes short circuit protection

Designed specifically for **high-voltage, high-reliability EV environments**, this PCB complies with Formula Bharat 2025 safety rules and integrates with the car's shutdown circuit. All PCB's components are thoroughly researched to pass temperature and and voltage ratings to make sure PCB runs as intended in all cases possible.

## 🛠️ Tools Used
- **EasyEDA** for schematic and PCB layout
- **NI Multisim** for simulation and validation
- **LTSpice** for behavioral checks
- Reviewed over 200+ datasheets for critical component selection for current , temperature and voltage rating.

## 📐 Key Features
- 600V system-rated layout with optimized creepage/clearance
- Multi-stage relay-based latching mechanism
- Compact, 2-layer PCB with thermal-aware routing

## 📸 Previews

| Schematic | PCB Layout |
|----------|-------------|
| *IMD_SCHEMATIC.png* | *IMD_PCB.png* |


