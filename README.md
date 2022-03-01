### Repository Content
* **/hardware** : Schematic files (.pdf) and Eagle design files (.sch and .brd)
* **/production** : gerber file for pcb manufacturing

You can purchase this product from [![Generic badge](https://img.shields.io/badge/Indonesia-Tokopedia-<COLOR>.svg)](https://www.tokopedia.com/geraicerdas/dwm1000-breakout-uwb-rtls-for-arduino-esp8266-esp32-indoor-location) 
[![Generic badge](https://img.shields.io/badge/Worldwide-Tindie-red.svg)](https://www.geraicerdas.com)

# DWM1000-Breakout-Module
DWM1000 Breakout Module with Voltage Level

This is modified version of the original designed by [prototyping-corner](https://github.com/prototyping-corner/DWM1000-Breakout). Because hard to find TXB0108DQSR chip, so we made change it to TXB0108PWR. Several decoupling capacitor is also added to filter out voltage spikes and pass through only the DC component of the signal

<p float="left">
<img src="https://images.tokopedia.net/img/cache/900/VqbcmM/2021/7/30/df1b53d5-c5d9-4541-9f03-82c13dbfb954.jpg" width=400 /> 
<img src="https://images.tokopedia.net/img/cache/900/VqbcmM/2021/7/30/236553de-f71d-49f5-88fb-bee2d3b55096.jpg" width=400 />
</p>

If you want to make your self, just download the gerber file in production folder. Send it to your fav pcb manufacturer. And dont forget to get the Bill of materials :
|Qty | Part Name | Parts | MPN |
| ------------- |:-------------|:-------------| -----:|
| 1 | DWM1000 | U2 | |
| 1 | TXB0108PWR | U3 | |
| 3 | SMD LED 0805 RED | L1, L2, L3 | |
| 3 | 1K ohm Resistor 0603 | R3, R4, R7 | |
| 5 | 10K ohm Resistor 0603 | R1, R2, R5, R6, R8 | |
| 4 | 100nF Capacitor 0603 | C1, C2, C3, C4 | |

## License
*We invests time and resources providing this open-source hardware, please support us by purchasing our products.*

*Designed by **[Insan Sains](https://www.youtube.com/insansains)** for **[Gerai Cerdas](https://geraicerdas.com)**, with contributions from the open source community. Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. See license.txt for additional information.*
