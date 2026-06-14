# APB-Based-SPI-Protocol


## APB-Based SPI Protocol Controller

This project implements an **APB (Advanced Peripheral Bus) based SPI (Serial Peripheral Interface) Controller** in Verilog RTL. The design enables communication between an APB master and SPI peripheral devices by integrating an APB slave interface with SPI master functionality. The controller supports configurable SPI modes (CPOL and CPHA), programmable baud rate generation, interrupt handling, and full-duplex serial data transfer.  

## Key Features

* APB3-compliant slave interface for register access and control.
* SPI Master communication with MOSI, MISO, SCLK, and SS signals.
* Configurable SPI modes (Mode 0, 1, 2, and 3).
* Programmable baud rate generator for flexible clock control.
* Full-duplex serial data transfer.
* Interrupt generation for transfer completion and status monitoring.
* Support for MSB-first and LSB-first data transmission.
* Modular RTL architecture for easy integration into SoC designs.  

## Project Architecture

The SPI Controller consists of the following modules:

1. **APB Slave Interface** – Handles APB read/write transactions and SPI register management.
2. **Baud Rate Generator** – Generates SPI clock (SCLK) based on programmable divider settings.
3. **SPI Slave Select Generator** – Controls the Slave Select (SS) signal and transaction timing.
4. **SPI Shifter** – Performs serial-to-parallel and parallel-to-serial data conversion for MOSI and MISO communication.   

## Applications

* Embedded Systems
* Sensor Interfacing
* Microcontroller-Based Designs
* FPGA and ASIC Communication Systems
* SoC Peripheral Integration 

## Technologies Used

* Verilog HDL
* RTL Design
* Finite State Machines (FSM)
* APB Protocol
* SPI Protocol
* FPGA/ASIC Design Flow


