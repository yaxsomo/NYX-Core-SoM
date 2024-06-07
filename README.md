<p align="center">
  <img src="https://github.com/yaxsomo/NYX-Core-SoM/assets/71334330/40ba0c4d-0810-43c6-b807-6d573773ee43" alt="nyc-core-som logo">
</p>

#
This repository is dedicated to the hardware development of Nyx Core SoM

## Introduction

The Nyx Core SOM (System On Module) is an innovative, open-source, high-performance single board computer designed by university students, for university students and companies. It serves as a versatile platform that can be adapted for a multitude of applications, including robotics, automotive, aerospace, and drone technology. At the heart of the Nyx Core SoM is the powerful Texas Instruments AM68 processor, featuring dual 64-bit Arm® Cortex®-A72 microprocessor subsystems, deep learning accelerators, and advanced vision processing capabilities. This project aims to provide an open-source hardware solution that can drive innovation and support the development of complex systems across various industries.

## Features


- Processor and Memory:
  - The Texas Instruments AM6852ATGGHAALZR processor includes up to dual 64-bit Arm® Cortex®-A72 cores running at 2 GHz, deep learning accelerators, and multiple vision processing accelerators.
  - The module is equipped with 2x8GB of LPDDR4 RAM and 512MB of on-board flash memory, ensuring high-speed data processing and sufficient storage for a variety of applications.
- Connectivity and Interfaces:
  - The SoM features a range of high-speed interfaces such as PCIe, USB 3.1, Ethernet, and multiple I2C, SPI, and UART ports, enabling seamless connectivity with various peripherals and sensors.
  - It also includes dedicated interfaces for camera modules (CSI), making it perfect for vision-intensive applications.
- Power Management
  - The onboard PMICs (Power Management Integrated Circuits) ensures efficient power distribution and management across the module, supporting both high-performance and energy-efficient operations.
- Customization and Flexibility
  - The Nyx Core SOM can be paired with different carrier boards designed for specific applications. This modular approach allows users to design custom solutions for robotics, automotive systems, aerospace projects, and more, simply by selecting the appropriate carrier board.
  - The system will embed a custom version of Linux (Helios Core OS), tailored to maximize the performance and capabilities of the hardware.

## Tech

The software used for this project is EasyEDA Professional. We choose this software because of its ease of use and its online library connected directly to LCSC manufacturer.

## How to use

You'll need to have EasyEDA PRO to open this project.
You can either use the online version, or the standalone version for Windows or MAC OS.

First, clone the repository :
```bash
git clone https://github.com/yaxsomo/NYX-Core-SoM.git
```

Next, go to EasyEDA :

- click on Import->EasyEDA(Professional)
- Select the .epro project from the cloned repository
- Configure the import parameters as follows :

<p align="center">
  <img src="https://github.com/yaxsomo/NYX-Core-SoM/assets/71334330/e4b7f9b2-b8f1-4b2a-9f34-ed993e4518cc" alt="easyEDA import parameters">
</p>

You're ready to go!

## Development

Stay up to date with the development by visiting the [Notion] page for the project. This page contains everything about the roadmap and project management. 

## License

You can check the [LICENSE](https://github.com/yaxsomo/NYX-Core-SoM/blob/main/LICENSE) file for more informations.

**Open-Source, Hell Yeah!**



