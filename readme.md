# arterytek-kicad-library
A library collecting Artery MCU footprints and symbols. It is maintained by [HorrorTroll](https://github.com/HorrorTroll). Huge thanks to all of our users who test new footprints and notify about bugs or issues.

The current latest release is made in/for KiCad 8.0 stable version.

## Disclaimer

### **I'm not assume any responsibility for broken PCBs or damages derived from errors in this library. Use at your own risk, and please open an issue or pull-request if you encounter any errors.**

Please do not use any footprint from this library with a symbol from another library (or the other way round). Pin numbering conventions are not always the same, and unless you check very carefully this can lead to broken PCBs.

## How to install
Open the KiCad "Plugin and Content Manager" (referred to as "PCM" from now on) and click on "Manage". Add a new entry with the plus sign and paste 

```
https://raw.githubusercontent.com/qmk-arterytek/arterytek-kicad-repository/main/repository.json
```

From this point on you will have "HorrorTroll KiCad repository" in your drop-down selection, and it will allow you to install (and update) arterytek-kicad-library through PCM - easy and hassle-free.

## Symbol libs
### MCU_Artery_AT32A40
* AT32A403A - Artery AT32A403A MCU series

### MCU_Artery_AT32F40
* AT32F402 - Artery AT32F402 MCU series
* AT32F403 - Artery AT32F403 MCU series
* AT32F403A - Artery AT32F403A MCU series
* AT32F405 - Artery AT32F405 MCU series
* AT32F407 - Artery AT32F407 MCU series

### MCU_Artery_AT32F41
* AT32F413 - Artery AT32F413 MCU series
* AT32F415 - Artery AT32F415 MCU series

### MCU_Artery_AT32F42
* AT32F421 - Artery AT32F421 MCU series
* AT32F4212C8T7 - Artery AT32F4212C8T7 MCU
* AT32F423 - Artery AT32F423 MCU series
* AT32F425 - Artery AT32F425 MCU series

### MCU_Artery_AT32F43
* AT32F435 - Artery AT32F435 MCU series
* AT32F437 - Artery AT32F437 MCU series

### MCU_Artery_AT32WB41
* AT32WB415CCU7-7 - Artery AT32WB415CCU7-7 MCU

## Footprint libs
### Artery_MCU
* LQFP-32_7x7mm - LQFP-32 (7x7mm) packages (e.g AT32F425KxT7)
* LQFP-48_7x7mm - LQFP-48 (7x7mm) packages (e.g AT32F405CxT7)
* LQFP-64_7x7mm - LQFP-64 (7x7mm) packages (e.g AT32F402RxT7-7)
* LQFP-64_10x10mm - LQFP-64 (10x10mm) packages (e.g AT32F407RxT7)
* LQFP-100_14x14mm - LQFP-100 (14x14mm) packages (e.g AT32F403AVxT7)
* LQFP-144_20x20mm - LQFP-144 (20x20mm) packages (e.g AT32F437ZxT7)
* QFN-28_4x4mm_ThermalVias - QFN-28 (4x4mm) packages (e.g AT32F421GxU7)
* QFN-32_4x4mm_ThermalVias - QFN-32 (4x4mm) packages (e.g AT32F415KxU7-4)
* QFN-32_5x5mm_ThermalVias - QFN-32 (5x5mm) packages (e.g AT32F421KxU7)
* QFN-36_6x6mm_ThermalVias - QFN-36 (6x6mm) packages (e.g AT32F423TxU7)
* QFN-48_6x6mm_ThermalVias - QFN-48 (6x6mm) packages (e.g AT32F413CxU7)
* QFN-48_7x7mm_ThermalVias - QFN-48 (7x7mm) packages (e.g AT32WB415CCU7-7)
* TSSOP-20_4.4x6.5mm - TSSOP-20 (4.4x6.5mm) packages (e.g AT32F425FxP7)

## 3D Models
All 3D models are created by KiCad
