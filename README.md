# USART Bluetooth LED Control with HAL Library on STM32
This project demonstrates how to control an LED connected to an STM32 microcontroller via Bluetooth using an Android app. The project uses the STM32CubeIDE development environment and the HAL library.
## Requirements
- STM32F4 Discovery board
- HC-05 Bluetooth module
- LED
- Breadboard and jumper wires
## Prerequisites
- STM32CubeIDE installed on your system
- An application to control an LED installed or built on your Android phone
## Installation
- Clone this repository to your local machine.
- Open STM32CubeIDE and import the project.
- Connect the HC-05 Bluetooth module to the STM32F4 Discovery board.
- Connect the LED to the board.
- Build and flash the code to the board.
## Usage
- Turn on the Bluetooth module by connecting it to power.
- Connect to the Bluetooth module from your mobile device.
- Open the application and connect to the Bluetooth module using the correct baud rate.
- Send the command led on to turn on the LED and led off to turn it off.

## Troubleshooting
- Make sure the HC-05 Bluetooth module is connected to the correct pins on the STM32 board.
- Make sure the LED is connected to the correct pin on the STM32 board.
- Make sure the Android device is paired with the HC-05 Bluetooth module.
- Make sure the Bluetooth LED Control app is connected to the HC-05 Bluetooth module.
- Make sure the app is sending the correct data to turn on/off the LED.
