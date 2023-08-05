# pmod_optical
#### PMOD to Optical (ADAT/SPDIF) Module

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0) [![Upload to - AISLER](https://img.shields.io/badge/Upload_to_-AISLER-ff8000)](https://aisler.net/p/new?url=https://raw.githubusercontent.com/mdovey/pmod_optical/dev/kicad/pmod_optical.kicad_pcb&ref=github)

PMOD module for interfacing with optical fibres using the JIS F05 connector (up to 16mbps). Typical applications are for digital audio using SPDIF (2 Channel) or ADAT (4/8 Channels).

![pmod_optical](./photos/pmod_optical.jpg)

| PMOD Pin | Name  | Direction | Description                    |
| -------- | ----- | --------- | ------------------------------ |
| 1        | TX    | Out       | Optical transmitter data       |
| 2        | TX_EN | Out       | Enable the optical transmitter |
| 3        | RX    | In        | Optical receiver data          |
| 4        | RX_EN | Out       | Enable the optical receiver    |

