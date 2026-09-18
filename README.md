# CoolerHackPad

CoolerHackPad is a 6-key Hackpad designed as a DIY alternative to a Stream Deck rather than a standard keyboard. VIA support is planned for a future update to make it a fully customizable macro pad.

---

## Features

* **Switches:** 6x Cherry MX-compatible key switches
* **Firmware:** QMK support (VIA support coming soon)
* **Enclosure:** 2-piece case (Top cover and Base)
* **Design:** Custom ventilation cutouts and styled USB port opening

---

## 3D Model

The case was modeled in **Fusion 360** and consists of two parts:
* **Base:** Holds the PCB, switches, and microcontroller. Fits together using M3 screws threaded directly into the plastic.
* **Top Cover:** Features cutouts for the key switches and ventilation holes for the PCB.

*Note: Parts of the case will be painted white to match the intended design aesthetic.*

![3D Model](https://github.com/user-attachments/assets/06a74e78-cb7f-4698-b031-d51d1176eea6)

---

## PCB

### Schematics
![PCB Schematic](https://github.com/user-attachments/assets/29279fcd-25ef-41b7-9eb4-528d1823af4d)

### PCB Design
<img width="1004" height="632" alt="image" src="https://github.com/user-attachments/assets/15edd661-7193-4a2c-bebf-ffa7ca1507f0" />

Designed in **KiCad**.

---

## Development Notes

This project was built entirely from scratch. AI assistance was used for software navigation and documentation reference—specifically for locating tools in KiCad and Fusion 360 (e.g., finding the move tool in Fusion 360, creating edge cutouts in KiCad) and formatting the QMK `keymap.c` firmware file. All hardware designs, 3D models, and code implementation were created independently.
