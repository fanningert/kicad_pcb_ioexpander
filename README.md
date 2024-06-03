# I²C IO-Expander

[![KitBot - Last PCB check](https://github.com/fanningert/kicad_pcb_ioexpander/actions/workflows/fabrication_check.yaml/badge.svg?branch=main)](https://github.com/fanningert/kicad_pcb_ioexpander/actions/workflows/fabrication_check.yaml)

Core goal is a pcb with the same pin outs, but with different i²C IO Expander. Castellated holes with secondary pin header holes are added, for direct PCB soldering. Secondary pin header holes are placed in a matrix of 2,54 mm (100 mils). Because of the fixed pin layout of the pcb, I created the boards in a four layer design.

# Versions

## SX1509

![3D render of PCB](doc/assets/pcb-SX1509-3d.png)

## PCA9685

![3D render of PCB](doc/assets/pcb-PCA9685-3d.png)

## Features

* Solder pads for I²C address
* Solder pads for I²C Pull-Up Resistor

## ToDos

* Create working GitHub workflow to create releases
* Optimize GitHub workflow for a more generic solution (no modification, when adding a new board)
