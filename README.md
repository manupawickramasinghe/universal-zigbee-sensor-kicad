# Universal Zigbee Sensor Board (ESP32-H2-Supermini)

![Board Image](https://github.com/manupawickramasinghe/universal-zigbee-sensor-kicad/blob/main/zigbee-universal-sensor-kicad.jpg) 

## Introduction

This repository contains the KiCad 9.0 project files for a universal Zigbee sensor board based on the ESP32-H2-Supermini module. This board is designed to be flexible and adaptable for various sensor applications, providing a compact and low-power solution for Zigbee-based IoT projects.

## Features

* **ESP32-H2-Supermini:** Utilizes the Espressif ESP32-H2-Supermini module, offering robust Zigbee connectivity and low power consumption.
* **Universal Sensor Interface:** Designed with multiple GPIO pins exposed for easy connection of various sensors (e.g., temperature, humidity, light, motion).
* **Power Supply Flexibility:** Supports various power supply options (e.g., battery, external power).
* **Compact Design:** Designed to be small and easily integrated into different enclosures.
* **KiCad 9.0 Project:** Fully documented project in KiCad 9.0 for easy modification and customization.

## Getting Started

### Prerequisites

* KiCad 9.0 or later installed.
* ESP32-H2-Supermini datasheet and documentation.
* Required sensor datasheets.
* A computer running a compatible operating system (Windows, macOS, Linux).

### Setup

1.  **Clone the Repository:**
    ```bash
    git clone https://github.com/manupawickramasinghe/universal-zigbee-sensor-kicad.git
    cd universal-zigbee-sensor-kicad
    ```
2.  **Open the Project in KiCad:**
    * Launch KiCad 9.0.
    * Click "File" -> "Open Project...".
    * Navigate to the cloned repository folder and select the `.kicad_pro` file.
3.  **Explore the Project:**
    * **Schematic Editor:** Open the schematic editor to view the circuit diagram. Examine the ESP32-H2-Supermini connections, sensor interfaces, and power supply circuitry.
    * **PCB Layout Editor:** Open the PCB layout editor to view the board layout. Inspect the component placement, routing, and board dimensions.
    * **Symbol and Footprint Libraries:** Ensure that the necessary symbol and footprint libraries are installed. The project should contain the needed libraries. However if you are missing any, they will need to be added.
4.  **Review the Datasheets:**
    * Refer to the ESP32-H2-Supermini datasheet to understand the pin functions and specifications.
    * Review the datasheets for the sensors you plan to use to ensure compatibility and proper connection.
5.  **Customize the Design (Optional):**
    * Modify the schematic and PCB layout to suit your specific sensor application.
    * Add or remove components as needed.
    * Adjust the routing and component placement for optimal performance.
6.  **Generate Gerber Files:**
    * Once you are satisfied with the design, generate Gerber files for PCB manufacturing.
    * In the PCB layout editor, click "File" -> "Fabrication Outputs" -> "Gerber Files...".
    * Configure the Gerber settings and generate the files.
7.  **Order PCBs:**
    * Use the generated Gerber files to order PCBs from a PCB manufacturer.
8.  **Assemble the Board:**
    * Solder the components onto the PCB.
    * Ensure proper orientation and soldering quality.
9.  **Programming the ESP32-H2-Supermini:**
    * Refer to the Espressif documentation for programming the ESP32-H2.
    * You will need a compatible development environment (e.g., ESP-IDF).
    * Develop and upload your firmware to the ESP32-H2-Supermini to control the sensors and manage Zigbee communication.
10. **Testing:**
    * Connect your sensors to the board.
    * Power up the board and test the functionality of the sensors and Zigbee communication.

