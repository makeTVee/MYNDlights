
# MYNDlights 💡

Addressable LED modification for the MYND open source Bluetooth speaker. Transform your MYND speaker with stunning, programmable RGB lighting synchronized to audio and custom animations.

![Matrix](./images/512_matrix.png)

## Features

- **WLED powered** - Full animation control
- **Audio Reactive** - LEDs respond to music and sound input
- **Easy Installation** - Mod-friendly design compatible with MYND speaker architecture
- **Open Source** - 3D files, KiCad files, firmware

The ESP32 is connected to the I2S data from the MYND Bluetooth module for audioreactive effects!

## Variants

### Gallery

#### Ring with 40 LEDs
![40_ring](./images/40_ring.png)

#### Teufel logo ring
![teufel_ring](./images/teufel_ring.jpg)

#### Ring with 100 LEDs

picture coming soon

#### Matrix with 512 LEDs

Using a "transparent" LED matrix as a speaker grid.

<img width="641" height="384" alt="image" src="https://github.com/user-attachments/assets/83827cb1-3cbb-445b-875b-d0e0413b199b" />

## Project Media

### Demonstration Videos

[Demo (Youtube)](https://youtube.com/shorts/J1kN-PWX2cs)

## Hardware Requirements

### Components Needed

- **MYND Bluetooth Speaker** (base unit)
- **Addressable LED ring or matrix** - WS2812B (NeoPixel) or similar 
- **Microcontroller** - XIAO ESP32-S3 boards
- **Wiring** - some FFC-cables

## Installation Steps
![Flex PCB](./images/flex.jpg)
![PCBs](./images/flex_and_pcb.jpg)
![Flex installation](./images/flec_on_connector.jpg)
![PCBs installed without battery](./images/installed_no_batt.jpg)
![PCBs installed with battery](./images/installed_batt.jpg)

## Development

### Project Structure

```
MYNDlights/
├── CAD/              # 3D models
├── Kicad/            # PCB files
```

## Contributing

Contributions are welcome!

## References

- [MYND Project](https://github.com/teufelaudio/mynd-hardware)

## License

This project is licensed under the BSD 2-Clause "Simplified" License.

## Acknowledgments

- MYND project team for the open source speaker design

---

