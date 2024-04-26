# Doron-Velta

## What's This?

I've never owned a Delta printer, but their unique design and mechanics have always fascinated me. As some of you may know, I contribute to maintaining [Danger-Klipper](https://github.com/DangerKlippers/danger-klipper), which involves testing various configurations and setups. In support of this work, Imac_29 (from the #pasteldenata) generously gifted me an FLSUN Q5. Interestingly, it never even saw the light of day in my home; I disassembled it on the very first day.

This all happened around SMRRF2023, where we humorously speculated that the Voron Design team would never release an official Delta design. What could be a better April Fool's joke than that? So, I went with it.

Originally, the plan was to create an April Fool's prank using the FLSUN Q5, printing parts to make it look like a Voron design. However, I ended up using just the Q5's arms and nothing else. I gathered a collection of spare parts I had lying around, began measuring, and started designing in CAD. After various splits and merges, I had a design reminiscent of the Voron Trident that I was happy enough. It wasn't complete but enough to share with other contributors.

[DoubleT](https://github.com/3DPrintingMods) was immediately on board and decided to build one himself. Within hours of discussing it with me, he had already ordered half of the parts. Interestingly, he managed to get his version printing even before I did.

I want to make it clear that I don't claim to have extensive CAD expertise or experience with Delta printers for this project, so please take my work with a grain of salt. My primary aim was, and remains, to explore Klipper firmware with Delta kinematics.

Yes, the printer works. Yes, it prints. Yes, it's aesthetically pleasing. And yes, it's far from being a perfect design. Most importantly, no, **this is not an official project by Voron Design**.

## Links

[DV-000 by rogerlz](https://www.reddit.com/r/voroncorexy/comments/1bsr2d7/special_serial_request_dv000_rogerlz/) ([YouTube](https://www.youtube.com/watch?v=DuFxvsZ5HEU))
[DV-001 by DoubleT](https://www.reddit.com/r/voroncorexy/comments/1bsrmby/special_serial_request_dv001_doublet/) ([YouTube](https://www.youtube.com/watch?v=adXSPTnKe_0))


## Pictures

![](images/dv-000.png)
![](images/dv-001.png)

## Bill of Materials (BOM)
| Category | Part | Qty | Notes |
| - | - | - | - |
| Frame | HFSB5-2020-500-TPW  | 3 | |
| Frame | HFSB5-2040-235 | 6 | |
| Axis | MGN9H 350mm-400mm | 3 | I used 400mm, DoubleT used 350mm  |
| Axis | GT2 Belt 9mm | ~3 meters | |
| Axis | GT2 20T Idler 9mm | 3 |  |
| Axis | Pin 5 x 20mm | 3 | |
| Axis | GT2 20T Pulley 9mm | 3 | G2Z Kit already includes it |
| Axis | Nema17 Steppers | 3 | Optional: LDO G2Z Kit, but don't do this :P |
| Axis | 210mm Fisheye Rods | 6 | I used: FLSUN Q5 arms [Aliexpress](https://www.aliexpress.com/item/1005006045340751.html) |
| Bed | 200mm x 5mm Alu Bed | 1 | [MandalaRoseWorks](https://mandalaroseworks.com/collections/doron-velta) |
| Bed | 200mm PEI Sheet | 1 | [Aliexpress](https://www.aliexpress.us/item/1005006287588997.html) |
| Bed | 200mm Magnetic Sheet | 1 | |
| Bed Mount | M3 x 6mm Ball Screw | 3 | [Aliexpress](https://pt.aliexpress.com/item/1005002808102402.html) |
| Bed Mount | 3 x 20mm Dowell Pin | 6 | |
| Bed Mount | Spring 
| Electronics | Kenoovo 170mm 200W AC Heater | 1 | [Keenovo](https://keenovo.store/collections/standard-keenovo-silicone-heaters/products/keenovo-round-circular-silicone-heater-delta-3d-printer-build-plate-heatbed-heating-pad) |
| Electronics | UHP-200-24 | 1 | |
| Electronics | SSR | 1 | |
| Electronics | MCU with 4+ drivers | 1 | Mounts for: SKR Pico and M5P |
| Electronics | Omron D2F-L microswitch | 3 | x4 if using Klicky |
| Toolhead | Any hotend supported by Mini SB | 1 | I used: Dragon |
| Toolhead | 3010 Axial fan | 1 | |
| Toolhead | 3010 Blower fan | 2 | |
| Extruder | G2SA / Sherpa Mini | 1 | |
| Screws | M3 x 6 | 40 | |
| Screws | M3 x 8 | 110 | |
| Screws | M3 x 10 | 12 | | 
| Screws | M3 x 12 | 10 | |
| Screws | M3 x 16 | 26 | |
| Screws | M3 x 20 | 2 | |
| Screws | M3 x 30 | 2 | |
| Screws | M5 x 8 | 24 | |
| Screws | M5 x 10 | 26 | |
| Screws | M5 x 12 | 36 | |
| Screws | M5 x 60 | 6 | |
| Screws | M3 Heat Inserts | 50 | |
| Screws | Yes | Many | |

## Thanks to

This was a fun project, and I have a lot of people to thank for, especially the VD (Voron Discord) contributors.

A heartfelt thanks goes out to DoubleT, who dedicated countless hours to CAD work, surpassing even my own time, and to Zruncho, whose guidance, support, and encouragement through direct messages and voice chats were invaluable.

I also want to extend my appreciation to pnewb, clee, hartk, Tetsu, Kyleisah, diem, imac_29 and many others for their support and contributions – you all have my sincerest thanks <3.

I would like to give special acknowledgment to the vendors: [Lab4450.com](https://lab4450.com) for supplying electronic components; ffb (Discord: ffb_9195) and [Seti](https://viperworx.uk) for supplying the PC and ACM panels; and [MandalaRoseWorks](https://mandalaroseworks.com) for the custom-made and beautiful Alu bed.
