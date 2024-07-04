# FLIGHT-CONTROLLER-PCB


# Custom Flight Controller PCB

Welcome to the Custom Flight Controller PCB project! This repository contains all the necessary files and information for creating a custom flight controller PCB using the STM32F40 microcontroller and various sensors and modules.

## Overview

This project aims to design and implement a custom flight controller for drones. The flight controller is built around the STM32F40 microcontroller and integrates various sensors and modules to provide comprehensive functionality.

## Components

### 1. STM32F40 Microcontroller
- **Description:** The main processing unit that handles tasks such as processing sensor data, controlling motor outputs, and managing communication protocols.
- **Role:** Brains of the flight controller.

### 2. NRF24L01 Wireless Module
- **Description:** Enables wireless communication for transmitting telemetry data and receiving commands.
- **Role:** Wireless communication.

### 3. MPU6000 Sensor
- **Description:** A gyroscope and accelerometer sensor that provides motion and orientation data.
- **Role:** Stabilizing the drone and providing accurate motion data.

### 4. BMP280 Sensor
- **Description:** A pressure sensor that measures altitude and atmospheric pressure.
- **Role:** Essential for flight dynamics and altitude hold.

### 5. NEO-6M GPS Module
- **Description:** A GPS module that provides precise location data.
- **Role:** Enables accurate navigation and waypoint tracking.

### 6. LM1117-3.3 Voltage Regulator
- **Description:** Provides a stable 3.3V supply to the components.
- **Role:** Power management.

### 7. Passive Components (Capacitors, Resistors)
- **Description:** Various capacitors and resistors used for decoupling, filtering noise, and setting timing parameters.
- **Role:** Ensure signal integrity and stability.

### 8. Other Components
- **LEDs:** Indicate the status of various operations.
- **Push Button:** Used for manual reset or mode selection.
- **Crystal Oscillator:** Provides a precise clock signal to the microcontroller.
- **JST Connectors:** Facilitate connections to external components and sensors.
- **Buzzer:** Provides audio feedback for alerts and notifications.

## PCB Design

The PCB design was created using EasyEDA, which includes:
- Schematic layout.
- Component placement.
- Trace routing.

## Getting Started

To get started with this project:
1. Clone the repository.
2. Open the schematic and PCB layout files in EasyEDA.
3. Review and modify the design as needed.
4. Generate the Gerber files and send them to a PCB manufacturer for fabrication.

## Demonstration

Watch the [YouTube video](https://www.youtube.com[) for a detailed explanation of each component and a demonstration of the PCB i](https://www.youtube.com/watch?v=k6ZKYF_iEr0&t=115s&ab_channel=yachitguliani)n action.

## Contributing

Feel free to fork this repository, make improvements, and submit pull requests. Contributions are welcome!



## Contact

For any questions or feedback, please reach out via [yachitguliani2005@gmail.com].

