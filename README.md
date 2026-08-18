# esp32_chargerbot
ESP32-S3 wheeled robot with IMU-based heading correction and time-of-flight collision avoidance that docks and wirelessly charges a custom open-source smartwatch. Custom PCB, Qi wireless charging, differential-drive servo mobility. Node 1 of a larger open-source privacy-first ecosystem.

Part 1 of an open-source privacy-first AI smartwatch project.

## Status
Early build — schematic design in progress (USB-C + power regulation block wired, ERC clean). Not yet at PCB layout, firmware, or chassis stages.

This README will grow as the project does.

## Planned feature set
- Custom 4-layer ESP32-S3 PCB
- IMU-based heading correction 
- Obstacle avoidance (dual VL53L0X time-of-flight sensors)
- Differential-drive mobility (2x continous-rotation servos + ball caster)
- Qi wireless charging for the companion smartwatch
 
## License
MIT - see [LICENSE](./LICENSE)