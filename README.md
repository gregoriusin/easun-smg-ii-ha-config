# easun-smg-ii-ha-config

Home Assistant configuration to monitor and control a EASUN SMG II inverter via USB or RS232 cable.

# Installation

Copy easun_smg_ii*.yaml files to the config directory or subdirectory.
In the easun_smg_ii.yaml file, set the correct port if other than ttyUSB0.

Add the following to /config/configuration.yaml:
```bash
homeassistant:
   packages:
     easun_smg_ii: !include [subdirectory/]easun_smg_ii.yaml
````
