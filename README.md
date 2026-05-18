# RETERMINT01 – RETERMINAL DM Interface Board

<div align="center">
  <img src="doc/gen/img/RETERMINT01-top.png" width="48%" alt="Top side" />
  <img src="doc/gen/img/RETERMINT01-bottom.png" width="48%" alt="Bottom side" />
</div>

RETERMINT01 is an interface board for the [reTerminal DM](https://wiki.seeedstudio.com/reterminal-dm/) by Seeed Studio. It adds a galvanically isolated industrial interface — **3× RS-485** bus, **isolated 24 V power supply** and the ability to **remotely switch off the power** of a connected field device via GPIO. All communication on the bus side is fully galvanically isolated from the reTerminal DM logic.

The board connects directly to the 40-pin GPIO header of the reTerminal DM.

## Features

- **3× RS-485** – galvanically isolated half-duplex channels (ADM2483xRW), up to 500 kbps
- **Isolated 24 V DC/DC** – 30 W Traco Power THN 30-2423WI, software-controllable (default OFF)
- **Remote power switching** – PS1 output controlled via `PWR_OFF` GPIO signal (active LOW)
- **5 V power module** – TI TPSM33606S5, powers the isolated RS-485 bus side
- **u-blox NEO-M9N GPS** – with u.FL antenna connector, USB configuration port and 1 F supercapacitor backup
- **Shielded RJ45 with LEDs** – for RS-485 field bus connection
- **ESD & overvoltage protection** – SM712 TVS on every RS-485 channel, USBLC6-2SC6 on GPS USB
- **2× 1 A fuse** – on 24 V input paths

## Schematic

[![Schematic](doc/gen/RETERMINT01-schematic.svg)](doc/gen/RETERMINT01-schematic.pdf)