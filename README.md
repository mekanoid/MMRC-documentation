Modern Model Railroad Control - Overview

## Documentation
For the MMRC concept you can find the following documentation. You can also find Readme files in the repositories for each of the MMRC software and the source codes are fully documented.


### MMRC Overview
[View the document](MMRC Overview.md).
_Swedish_

This document describes the concept of MMRC and explains how to use it and how it communicates. It is a **work in progress**.


### MMRC Convention
[View the document](MMRC Convention.md).
_English_

The convention defines the structure of MQTT topics and the properties to use in MMRC.

<!--
### MMRC Properties
[View the document](MMRC Properties.md).
_English_

Description of the different payloads all MMRC properties should use. This document is a **work in progress**.

### MMRC Settings
[View the document](MMRC Settings.md).
_Swedish_

Here you find a description (in swedish) of the more general settings you can do for a MMRC client.
-->


### MMRC Wifi AP
[View the document](MMRC Wifi.md).
_Swedish_

A concise description on how to configure a Raspberry Pi to act as an standalone Access Point and MQTT broker.


### MMRC MQTT broker
[View the document](MMRC MQTT broker.md).
_Swedish_

This document describes how to install the Mosquitto MQTT broker on a Raspberry Pi (or any Linux distribution, actually).


## Hardware
When using MMRC at your model railroad, you may need some hardware to complete the installation.

### MMRC 3D print
[View the repository](https://github.com/mekanoid/MMRC-3dprint)
In this repository I put some 3D printing files that can be useful when you want to use MMRC at your model railroad.

### MMRC PCB
[View the repository](https://github.com/mekanoid/MMRC-pcb)
Here you can find some Printed Curcuit Board layouts that can be used when building different types of MMRC clients.


## Software
Since each MMRC client has its own specific software, there are several repositories to choose from. Right now you can find the following:


### MMRC 2turnout
[View the repository](https://github.com/mekanoid/MMRC-2turnout)

This application controls two separate 2-way turnouts independently. You can control each turnout with a physical button or from a remote client/MQTT app and you can have LEDs indicating the turnout position.


### MMRC Two signal
[View the repository](https://github.com/mekanoid/MMRC-twosignal)

This application controls two separate signals from two different turnouts independently. It's made for Swedish light signals and can control both 2, 3, 4 or 5 light signals.
At the moment this is **a work in progress** and the application just controls one 2-5 light signal.
