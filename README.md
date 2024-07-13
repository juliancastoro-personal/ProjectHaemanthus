# ProjectHaemanthus
An integrated plant monitoring and watering system.

<img src="docs/project_plan.png" alt="POC plans" width="300"/>

## Table of Contents
1. [Introduction](#introduction)
2. [Components](#components)
3. [Installation](#installation)
4. [Usage](#usage)
5. [POC Plans](#poc-plans)
6. [Contributing](#contributing)
7. [License](#license)

## Introduction
ProjectHaemanthus is an automatic plant watering system designed to keep your plants healthy and hydrated. By using a Raspberry Pi Zero WH, a capacitive moisture sensor, and a water pump, the system monitors soil moisture levels and waters the plants as needed.

## Components
- **Raspberry Pi Zero WH**
- **Capacitive Moisture Sensor**
- **Water Pump**
- **Relay Module**
- **Jumper Wires**
- **Power Supply for Raspberry Pi**


# Dependencies
1. Python 3.12

## Installation
### Step 1: Set Up Raspberry Pi
1. Install Raspberry Pi OS on your Raspberry Pi Zero WH.
2. Connect your Raspberry Pi to a power supply, monitor, keyboard, and mouse.
3. Update and upgrade your system:
   ```bash
   sudo apt-get update
   sudo apt-get upgrade