# STeaMi Reference Design

Welcome to the repository for the **STeaMi Reference Design**. This repository contains all the electronic and mechanical design files for the STeaMi learning board, a versatile and feature-rich platform for teaching programming and electronics.

## Overview
The **STeaMi board** is built around the **STM32WB55 microcontroller** and is designed to offer:

- **Connectivity:** BLE (Bluetooth Low Energy) communication capabilities.
- **Extensibility:** Integration options with Jacdac and Qwiic connectors.
- **Versatility:** A wide array of onboard sensors.
- **Compatibility:** Seamless integration with the **micro:bit ecosystem**, allowing educators to continue using existing materials while leveraging the advanced capabilities of STeaMi when needed.

This board is an essential tool for educators aiming to explore STEAM (Science, Technology, Engineering, Arts, Mathematics) education.

## Key Features

### Hardware
- **Microcontroller:** STM32WB55 with dual-core architecture (ARM Cortex-M4 and Cortex-M0+).
- **BLE Support:** Bluetooth Low Energy for IoT and wireless communication projects.
- **Connectors:**
  - **Jacdac:** For chaining external modules and simplifying connections.
  - **Qwiic:** For seamless sensor and peripheral integration.
- **Onboard Sensors:**
  - Environmental sensors (temperature, humidity, pressure).
  - Motion sensors (accelerometer, gyroscope, magnetometer).
  - Proximity, light, and other utility sensors.

### Compatibility
- **micro:bit Ecosystem:** Fully compatible, allowing educators to reuse existing peripherals and lessons.
- **Plug-and-play Design:** Simplifies adoption in classrooms and workshops.

### Mechanical Design
- Compact form factor, ensuring ease of use.
- Mounting options compatible with standard educational kits.

## Project Background
The STeaMi board was developed as part of the **I-NOVMICRO** project ([Learn more](https://campus-industriefutur-sud.com/i-novmicro/)) and the **MAGNETICS** project ([Learn more](https://www.magnetics.edu-up.fr/)). These initiatives aim to advance innovative tools for education and training.

## Repository Contents
- **Electronics Design Files:** Schematics, PCB layout files, and BOM.
- **Mechanical Design Files:** CAD models for the enclosure and mounting options.

## Getting Started
1. Clone this repository:
   ```bash
   git clone https://github.com/steamicc/steami-reference-design.git
   ```
2. Review the documentation folder for setup instructions.
3. Open the design files using your preferred CAD and PCB design tools.

## License
All resources in this repository are released under an open license and are protected under the stewardship of the **STeaMi Foundation**. See the `LICENSE` file for more details.

## Contributions
We welcome contributions to enhance the STeaMi board. Whether you’re fixing a bug, adding a feature, or improving documentation, feel free to submit a pull request.

## Resources
- [STeaMi Official Website](https://www.steami.cc/)

## Support
If you have any questions or need assistance, please open an issue in this repository or contact us via [STeaMi contact mail](mailto:contact@steami.cc).

---

Thank you for supporting STeaMi and STEAM education!

