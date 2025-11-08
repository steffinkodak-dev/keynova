# KeyNova (MVP)
KeyNova is a mobile app + LED key strip that lets anyone learn songs fast by lighting the exact piano keys to press in real time.

## MVP Scope
- Input: MIDI file
- Output: LED strip lights correct keys at tempo
- Control: BLE from phone (play/pause, tempo)

## Folders
- app/: mobile app
- firmware/: ESP32 (BLE + LEDs)
- hardware/: BOM, wiring, enclosure
- docs/: protocols, calibration
- media/: demo assets

## Quick Start
- Firmware: ESP32 + WS2812B test (LED chase)
- App: BLE scan/connect to "KeyNova-XXXX" and send a test pattern

## License
MIT
