# LabSCim

This is a phy simulator to be plugged in the major IoT platforms. 

For now we are planning to provide drivers for:

TSCH, CSMA:

* Contiki-ng - https://github.com/contiki-ng
* 6lbr (we hope that both can compile with the same drivers) - https://github.com/cetic/6lbr/wiki

LoRa:

* LoraMac - https://github.com/Lora-net/LoRaMac-node
* Lora Packet forwader (we hope that the upper layers may execute without modification) - https://github.com/Lora-net/packet_forwarder

Bluetooth:

* Zephyr-os - https://github.com/zephyrproject-rtos/zephyr

The starting point is omnet-tsch, whose disclamer is below:

# TSCH

OMNeT++ simulation model for IEEE 802.15.4e Time Slotted Channel Hopping (TSCH)

## Compatibility

This model is developed and tested with the following library versions

*  OMNeT++ [5.5.1](https://omnetpp.org/software/2019/05/31/omnet-5-5-released.html)
*  INET [4.1.1](https://github.com/inet-framework/inet/blob/v4.1.1/WHATSNEW)

**For Windows users**: please note that compilation/linking does only seem to work with the **Clang** Compiler (as it is the default for OMNeT++ 5.5.1) and commit [505af4d](https://github.com/inet-framework/inet/commit/505af4d10f32d0a3aa505dabbe1ed68bdbb2a6da) applied to INET 4.1.1
