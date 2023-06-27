# Standard_Cell_Project

This Project is designed using Open Source GLADE Software (https://peardrop.co.uk/) using 2.5um Technology Node. GLADE is an IC layout and schematic editor capable of reading and writing common EDA formats.

In this Project, I have designed the Standard cell of 7-Track of logic gates (AND, NAND, OR, XOR) and Combinational cells (2x1MUX, HA) and simulating them on ttt corner using Glade Software. Here pitch is considered with via-overhung and without via-overhung.

For Via-overhung, Pitch is 8.5u with cell height of 51um. Beta is chosen as 1.528 with width of PMOS is 20.25um and that of NMOS is of 13.25um.

For without Via-overhung, Pitch is 5.5u with cell height of 33um. Beta is chosen as 1.583 with width of PMOS is 9.5um and that of NMOS is of 6um.

Simulation is done using Xyce Simulator.

This project consists of Schematic of logic gates, Creation of symbol and simulating the symbol using ttt corner.

Some of the terminologies that is used in standard cell

A standard cell library is a collection of well defined and appropriately characterized logic gates that can be used to implement a digital design.

Track:- It is a unit to define the height of a standard cell.

Pitch:- The distance between two tracks is called Pitch.

Standard Cell height = Pitch * (N-1), where N is number of Tracks.

Beta Ratio:- Ratio of width of PMOS to that of NMOS.

In future I will design layout of all the logic gates and combinational cells that were used in this project.
