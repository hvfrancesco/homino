A diy Arduino compatible board with some moloko vellocet addition
(e.g. featuring on-board 433Mhz RF transceiver for experiments on home-automation and microcontroller communication)

The board is based on Arduino open-hardware design, but completely revised in order to be made using a single-sided copper board and techniques like toner-transfer etching.
The connector in Homino are arduino shields compatible, but the board comes in Altoids tin can format.

Homino replicates all the functionalities of Arduino, with some limitations:

- No on-board usb-to-ttl, you will need an external usb-ftdi cable to program it (however auto-reset works flawlessly too)
- No ISP connector

There is fortunately some nice additions too:

- Selectable 5V/3.3V operation mode (through a jumper)
- On-board RF comunication based on cheap 433Mhz radio modules like the ones from Seedstudio, allowing the interoperability with low cost 433 MHz remote control devices. Homino will most likely work with all popular low cost power outlet sockets.
Communication between several Homino boards or any other 433Mhz RF enabled microcontroller is also possible.



Useful links:

Arduino libraries for RF projects
- http://code.google.com/p/rc-switch/
- http://www.airspayce.com/mikem/arduino/

Low-cost RF modules compatible with Homino
- http://www.seeedstudio.com/depot/433mhz-rf-link-kit-p-127.html?cPath=19_22
