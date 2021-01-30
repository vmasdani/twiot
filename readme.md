# TWIoT
Compilation of hacky internet of things schematics & codes/scripts which aim to help monitor and automate things around my house--in a third-world country--as cheap and robust as possible.

### Ecosystem
The ecosystem mostly uses the programming language Rust and Elm, which are the most robust programming languages in the market. Machine-to-machine communication uses MQTT while storage uses SQLite. MQTT is chosen because it is one of the most lightweight protocols which is compatible with Arduino + ESP8266.

### Submodules
To init submodules, execute:
```
git submodule update --init --recursive
```

### (Dev) updating submodules
To update all submodules, execute:
```
git submodule foreach git pull origin main
```

Roadmap:
- Gateway - Orange Pi Zero (WIP)
  - Generic devices & sensors database (WIP)
  - OLED QR view (WIP)
  - Management Console Frontend (0%)
- Smart Garden
  - Gateway backend (WIP)
    - Manual watering schedule (WIP)
    - Automatic watering (0%)
  - Actuators (WIP)
    - Solenoid valve controller (WIP)
  - Sensors (0%)
    - Soil Moisture Logger (0%)
- Energy Monitor
  - Gateway backend (0%)
    - Rooms catalog (0%)
  - Sensors (0%)
