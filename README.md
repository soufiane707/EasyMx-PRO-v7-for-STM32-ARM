

### README

This repository contains firmware tests and experiments for the **EasyMx PRO v7 for STM32** development board featuring the **STM32F107VCT6** microcontroller.
The goal is to evaluate various peripherals, sensors, and communication protocols using **STM32CubeIDE** and the **HAL API**.

#### Scope

* Testing digital and analog sensors
* Interfacing with Click boards via **mikroBUS™** sockets
* Communication protocol validation: **I2C**, **UART**, **SPI**, and others
* Storage testing using **EEPROM**, **on-board Flash**, and **microSD card**
* Evaluation of **Ethernet** interface for network-based applications
* Audio codec and buzzer functionality tests
* Touch screen and display interaction via the **EasyTFT**(based on HX8347D 8080 parallel 8-bit graphics driver) module with LVGL 

Development and debugging are performed through **STM32CubeIDE** using the **integrated hardware debugger and programmer** based on **ST-LINK V2**, utilizing the same standard ST drivers.

A reference image of the setup will be included for documentation purposes.



<img width="850" height="713" alt="image" src="https://github.com/user-attachments/assets/d1656d55-67b5-445f-9684-12be5b49d824" />
