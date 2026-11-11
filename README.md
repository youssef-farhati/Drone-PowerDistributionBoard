# Open-Source Quadcopter PDB & Flight Controller

A custom-designed 2-layer power distribution board (PDB) and integrated flight controller built for 2205/2207 brushless motors. Designed with a dedicated bottom ground return plane (`B.Cu`) and high-current top-layer power routing (`F.Cu`).

## 🚀 Project Status
- [x] Schematic Capture & Netlist Verification
- [ ] PDB PCB Layout & DRC Clearance Check
- [ ] Hardware Fabrication & Assembly
- [ ] Firmware Development (Sensor telemetry & motor mixing)
- [ ] Maiden Flight Testing

## 📂 Repository Structure
- **`hardware/`** - KiCad schematics, layout files, and manufacturing gerbers.
- **`firmware/`** - Low-level C code for sensor integration and flight control loops.
- **`docs/`** - Component datasheets, pinouts, and system architecture notes.

## 🛠️ Specifications
- **Board Architecture:** 2-Layer PCB (`F.Cu` for power/signals, `B.Cu` for solid `GND` return plane)
- **Target Motors:** 2205 / 2207 Brushless Motors (30A–35A current draw)
