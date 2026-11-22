# esp32-flight-ctrl-mvp
ESP32 flight controller MVP: blink, MAC address check, Wokwi MPU6050 &amp; joystick simulation.

# esp32-flight-ctrl-mvp

ESP32 flight controller MVP: blink, MAC address check, Wokwi MPU6050 & joystick simulation.

## Hardware & MAC Address

- **Board A (`ESP32-D0WD-V3 rev3.1`)**: `d4:e9:f4:a2:2a:18`

## Today's Progress

- [x] Set up Arduino IDE and ESP32 board support; verified serial port (`COM3`)
- [x] Tested onboard LED blink and Serial Monitor output (`01_blink_serial/`)
- [x] Read and recorded ESP32 MAC address (`d4:e9:f4:a2:2a:18`) (`02_mac_reader/`)
- [ ] Wokwi simulation with ESP32, MPU6050 (roll / pitch), and analog joystick (X / Y) (`03_wokwi_imu_joystick/`)
- [ ] Upload code and simulation screenshot to GitHub (`docs/`)

## Project Structure

- `01_blink_serial/` — LED blink and Serial Monitor test
- `02_mac_reader/` — ESP32 MAC address reader
- `03_wokwi_imu_joystick/` — Wokwi MPU6050 attitude + joystick simulation
- `docs/` — MAC notes (`mac_notes.md`) and Wokwi simulation screenshots
