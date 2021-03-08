## Battery Management System Dev Board for LTC68xx

This board is original develped for [Spartan Racing Electric](http://sr-e.org), any other FSAE teams and projects are welcome to use

It can directly talk to LTC68xx evaluation board via RJ-45, such as [DC2259A](https://www.analog.com/en/design-center/evaluation-hardware-and-software/evaluation-boards-kits/dc2259a.html)

MIT license, you can use or modify it as you want

### Features
* STM32F303CC6 Microcontroller
* LTC6820 Isoalted SPI interface and transformer
* TI SN65HVD232 CAN transceiver
* CP2012 USB to UART bridge
* On board DB9 connector and termination resistor
* RJ-45 connector for LTC68xx dev board
* USB-C

**About Manufacturing**

It's a 4 layers 50mm x 50mm board, which can be printed in JLC PCB cheaply in case you don't have a sponsorship

The smallest SMD size is 0603, it is designed for hand soldering and reworking

![alt text](/doc/bms_dev_board_3d.png)

Schematic
![alt text](/doc/bms_dev_board_schematic.png)
