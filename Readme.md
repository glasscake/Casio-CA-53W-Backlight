# Casio-CA-53W Backlight Modification PCB

<div align="center">
<img src=pictures/Demo.JPEG height="550">
</div>

## Description
This is a PCB that adds backlight functonality to Casio-CA-53W style watches. It could potentially work with other Casio watches as well.

This project is still very green, a rev A board has been produced and is being tested. significant redesigns are still needed to improve preformance and relability in assembly.
Watch the project and see how development goes.

The design files are made in [KiCad](https://www.kicad.org/) an open source PCB design software.

## Make Your Own
Rev A boards have been produced from JLCPCB uploading [Rev A.zip](Gerber%20Files/Rev%20A/Rev%20A.zip) to JLCPCB's or other PCB manufacturer's online portal and selecting flex PCB with ENIG sohuld get you boards similar to myown.
Once a suitable design has been found more thorough ordering instructions will be provided. The current design also has a stiffener, this has no benifit and is not required.

Current limiting resistors can be ommited if diodes with a foward voltage close to 3.0v are carefuly chosen. I am using [Vishay VLMW15 serires](https://www.digikey.com/en/products/detail/vishay-semiconductor-opto-division/VLMW1500-GS08/3504672) 0402(imperial) LEDs at the moment. These LEDs have a typical forward voltage of 2.9 volts which means when using the Casio's 3.0v
battery the foward current is around 5mA very well within the 20mA rating of the componets. So shunts or solder bridges may be used instead.
0402 is the smallest componet the average enthusiast will be able to solder by hand.
the move to 0201(imperial) LEDs may come if 0402 componets are too large to fit and retain splash resistance in the watch.


## Copyright
Copyright 2025 NuE All rights reserved

Private usage of this project by an individual with no intention to resell or distribute at profit the finished PCB, preassembled PCB, raw PCB, design files, or any item derived from this project is completly allowed.

At the moment this project is not open source. I am trying to figure out a license type that would allow contribution and private use but disallow an individual or company the ability to resell the componets, finished PCB, or design.