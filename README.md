# fudge board
------ 
## Important!
This board charges batteries but does NOT run off batteries connected to the BAT and GND terminals. I plan to make a revised version where this is changed.


This is an RP2040 dev board created based off the <a href="https://github.com/KaiPereira/build-a-devboard">guide</a> from Blueprint at Hackclub!

### Features
- RP2040 Chip
- 12MHz Crystal Oscillator
- Many GPIO Pins
- a 1 Cell Lipo/Li-ion Battery Charger
- LED connected to GPIO
- USB-C
- 16MB of Flash Memory
- LDO Power Regulator

#### KiCad
The entire board was made with this software! The pictures below are taken from KiCad!

<strong>Schematic</strong>

<img src="/assets/schematic.svg">

<strong>PCB</strong>

<img src="/assets/pcb.svg" style="zoom: 350%">

#### JLCPCB
Here is a sample of what manufacturing the board might cost.

<strong>BOM</strong>

<img src="/assets/bom.png">

<strong>Final Price</strong>

<img src="/assets/cart.png">
<img src="/assets/cart2.png">

#### Excalidraw
All silkscreen drawings were made with this handy website.
#### Extra
From this project I learned a lot more about how common communication interfaces like SPI, UART, and I2C work. I quickly picked up on electronics basics such as the theory behind decoupling capacitors, pull-up/pull-down resistors, and common electronics components (flash memory ics, crystal oscillators, etc.). I hope with this knowledge, I can continue on to put together a little single board computer, like the common Raspberry Pi.
