# Eagle-Component-Library
A slowly growing compilation of components used in various PCB/PCBA projects done with Eagle EDA software (Version 7.x).

## Description

Starting point for an Eagle lib search is usually https://componentsearchengine.com/ or https://www.snapeda.com/parts.  

However, in a lot of my projects some components get harvested from old devices and re-used in new ones. Then it's almost impossible to find an Eagle lib for it. This is especially true for many connectors, terminals, chokes etc. Other components don't seem to be exotic but an Eagle lib can't be found on the internet despite a lengthy search.  

Requesting a lib for a special component e.g. on componentsearchengine.com would be an option, but it got to be listed there. If not, you are forced to build your own one. Sometimes a lib was found but has been slightly changed in order to fit special project requirements (e.g. keepout/restrict layer added, symbol amended, footprint narrowed/enlarged, etc).  

Be aware, this lib might contain errors, so use at your own risk.


## List of available components
If known then the source I got this component from is included in brackets. Most of them are available from different sources though.

### Connectors, Headers, Sockets, etc.
* AA/AAA Through-Hole Battery Holder (Ali)
* B2B-PH-K - JST PH2.0 Male Header 2-Pin (Reichelt/Ali)
* B6B-PH-K - JST PH2.0 Male Header 6-Pin (Reichelt/Ali)
* AKL-073-xx Terminal Block (Reichelt)
* AKL-094-xx Terminal Block (Riacon, Reichelt)
* MA01-1, MA02-1, MA10-1 - Single Row Pin Header 2.45mm Pitch (Ali)
* Micro-USB Connector Type-B, 5-pin (Ali)
* USB-C-4105-GF-A, USB-C-TYPE-C-019, etc. - Various SMD USB-C Connectors (LCSC, JLC)
* NEB21R Lumberg - DC Supply Socket Male 5.5/2.1mm (Reichelt, Mouser)
* NEB25R Lumberg - DC Supply Socket Male 5.5/2.5mm (Reichelt, Mouser)
* SMA Connector (Ali)
* RCA3 Female Cinch CONNECTOR, RCA Jack (Reichelt)
* RJH3201N - RCA Stereo Connector (harvested from Technics ST-G570)
* SJS9236 - AC Power Inlet (harvested from Technics ST-G570)
* Misc. Jumpers/Bridges, Solder Pads

### Switches
* B3U-1000P, TS-1064S-A1B2-D4 - Ultra-small surface-mounting tactile switches with high contact reliability, 2.5x3.0mm (LCSC, JLC)
* BPS-2288 - Push Switch (Ali)
* PTS526XX - Tactile SMD Micro Switch, 5x5mm (LCSC)
* PTS636-SM25 - Tactile SMD Micro Switch (LCSC)
* SS-12D00-G3 - Sliding Switch 3-Pin (LCSC)

### ICs
* AD5452 - DAC Converter with serial interface
* AMS1117-xx - Voltage Regulator LDO
* LM4040, B589 - Voltage Reference
* ICM7555 - General Purpose Timer
* K78xx-2000R3 - Voltage Regulator
* LM78S40 - Universal Switching Regulator from TI
* MCP130T-XXX - Microcontroller Supervisory Circuit with Open Drain Output
* MCP1702 - Voltage Regulator LDO
* PGA-103+ - MMIC 50-4000MHz
* PMBFJ620 - Dual N-Channel JFET
* SDA4212 - ECL Divider 256:1 or 64:1
* VS1053B - 18bit-Audio Codec 48-Pin LQFP
* WM8805 - 8:1 Digital Interface (SPDIF) Transceiver with PLL
* YX8018 - Simple Solar Light Controller (Ali)

### Modules
* AD9833 DDS Module (Ali)
* AD9850 DDS Module (Ali)
* Arduino Nano Board with ATmegaXX8P and Mini-USB (Ali, Elecrow)
* ESP32-T Board for ESP32-Bit Modules (Ali)
* LMH6321 soldered on a SOIC-8 to DIP-8 Adapter
* ST7735 on a 1.8" TFT-Module with SD-Card-Slot (Ali)
* VS1053/VS1053B Audio Module with SD-Card Slot and Microfone, red (Ali)
* W5500 Wiznet Ethernet Modul (Ali)

### Buzzers/Transducers
* AL-60SP05 - U ~4-7VDC, Freq ~2300Hz, Dia 11.8mm (Reichelt)
* TDB-05 - U 4-6.5VDC, Freq ~2300Hz, Dia 12mm (Reichelt)

### DC-DC Converter Modules
* ARTESYN AEE 40W series - 40W DC-DC Converter, regulated (Ali, Mouser) 
* MORNSUN URB_LD-30WR3 - 30W DC-DC Converter, regulated (Ali, Mouser) 
* OKI-78SR, OKI515W36C, OKI3315W36C - Murata DC-DC Converter 7.5W/5Vout (Reichelt, Mouser)

### Transformers/Chokes/Inductors/Beads
* 09HCP - Fastron Inductor Series 
* 390-A005 - Common Mode Choke (harvested from old power supplies)
* Ferrite Beads in different sizes
* Gerth 387.XX - Transformer, EI 38/13,6 230V/3.6VA (Reichelt)

### Semiconductors
* 1.5SMCXXA Series - Suppressor Diodes (Mouser, Ali)
* B40C5000/3300 - Rectifier Bridge, 40V/5A, Diotec
* BFW92 - NPN Silicon High-Frequency Transistor
* BT137B-X00 - Triac 600V/8A, SOT404 Package
* P6KEXXCA - Transient Voltage Suppressor Diode (Ali, Mouser)

### Misc
* NA5W-K - Miniature Relais for Signal Switching, Takamisawa (Mouser)
* OMH 125 - SMD Fuse Holder Block, 125V/5A, 12x5.2mm (Reichelt)
* Various TO220 Heat Sinks (Ali) 
* Fiducials needed for PCB panel production
* ...

