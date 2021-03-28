# CO<sub>2</sub>-Sensor-Attnode mit MH-Z19
A small functional AddOn CO<sub>2</sub>-Sensor to use with a [attno.de v3](https://attno.de) and MH-Z19-CO<sub>2</sub>-Sensor

 pictures from [@seiichiro0185](https://twitter.com/seiichiro0185?s=20) | &nbsp;
 ---------------------------------------------------------------------- | --------
 ![MH-Z 19 offen](https://github.com/theArcher73/attnode_addon_mh-z19/blob/main/3d-files/mh-z19_1.png) | &nbsp;
 ![MH-Z 19](https://github.com/theArcher73/attnode_addon_mh-z19/blob/main/3d-files/mh-z19_2.png) | ![MH-Z 19](https://github.com/theArcher73/attnode_addon_mh-z19/blob/main/3d-files/mh-z19_3.png)

You can find more information and the latest firmware at [attno.de v3](https://attno.de). [@seiichiro0185](https://twitter.com/seiichiro0185?s=20) is continuously developing the software, which is why it is only linked here.

This pcb allows the extension of the [attno.de v3](https://attno.de) with the possibility to be operated with 5V-15V operating voltage as well as CO<sub>2</sub> measurement by means of MH-Z19.

The measured values of the CO<sub>2</sub> sensor as well as the connection via LORAWAN<sup>(TM)</sup> can be visualized directly at the device by the integrated RGB-LED's, parallel to the transmission to a LoRa-Network-Server (LNS).

The use of the MH-Z19C is strongly recommended. However, this sensor drifts over time so regular calibration is required.
The sensor can be purchased over the Silk Road or directly from German dealers.

Special thanks to [@seiichiro0185](https://twitter.com/seiichiro0185?s=20), [@TwentySixer](https://twitter.com/Twenty_Sixer?s=20) and [@nottheedge](https://twitter.com/nottheedge?s=20) for their support.

front view | rear view
---------- | ---------
![front view](https://github.com/theArcher73/attnode_addon_mh-z19/blob/main/kicad-project/img/board_front.png) | ![Rear view](https://github.com/theArcher73/attnode_addon_mh-z19/blob/main/kicad-project/img/board_rear.png) 

In the folder 3d-files are stl-Files for a tiny housing from [@seiichiro](https://twitter.com/seiichiro0185).

 front-part MH-Z19C | rear-part CO<sub>2</sub>-Sensor Micro-USB | rear-part CO<sub>2</sub>-Sensor USB-C
 ------------------ | ----------------------------------------- | -------------------------------------
![MH-Z 19 front part](https://github.com/theArcher73/attnode_addon_mh-z19/blob/main/3d-files/attnode-mhz19c-front.png) | ![CO<sub>2</sub>-Sensor rear part USB Micro](https://github.com/theArcher73/attnode_addon_mh-z19/blob/main/3d-files/attnode-co2-back.png) | ![CO<sub>2</sub>-Sensor rear part USB Micro](https://github.com/theArcher73/attnode_addon_mh-z19/blob/main/3d-files/attnode-co2-back-usbc.png) 
&nbsp; | [passende Breakout-Boards Micro-USB](https://www.amazon.de/dp/B07RDHNL9H/ref=cm_sw_r_oth_apip_Hl8EULSynzB3m) | [passende Breakout-Boards USB-C](https://www.amazon.de/dp/B01787RJW4/ref=cm_sw_r_oth_apip_VpbGjvT7G7Qvm)

The rear parts of the enclosures for Micro-USB or USB-C are planned for the use of ready-made breakout boards with USB-C or micro USB. The button for ad-hoc measurements or calibration can be glued into the housing.

LORAWAN is a registered trademark of [Semtech](https://www.semtech.com/)
