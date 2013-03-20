DIGIO
=====

Cypress FX2 Source Code for the DIGIO

What This Contains
=====

This repo contains the uVision project and all associated source files to build the DIGIO USB .hex and .iic files.
You'll need to install the Cypress development tools (http://www.cypress.com/?rID=14319) to create the .iic file and load the firmware.
The source itself uses a very simple opcode then data protocol via endpoint 1.
The opcodes cover both I2C and SPI programming, as well as some information on version, FPGA enable/disable, etc.

VID/PID Pair
=====
This project currently uses a Cypress VID (0x04b4) and random PID, but will hopefully be updated to use an open source VID/PID pair.