# nixified-nebra-meshtastic
NixOS image for a Nebra HNT that’s been converted into a Meshtastic node

## Goals

The general idea is:

- everything is declarative and easily reproducible 
- all the needed settings like SPI & I2C & the like are already set
- runs official docker container pinned to the desired version 
- automatically pulls in [@wehooper4](https://github.com/wehooper4)’s [config file for 2w hat](https://github.com/wehooper4/Meshtastic-Hardware/blob/main/NebraHat/NebraHat_2W.yaml) 
- Tailscale is preinstalled 
- firewalling is setup
- meshtastic cli will be installed 
- clear instructions for setting a hostname,  securing ssh, configuring needed network settings (wired and wireless), and utilizing Tailscale would be included
