# Credits

Game code, story and the code-drawn characters, furnaces and wrench: Tinker's War.

## Art

| Asset | Author | Used for | Files in `art/` |
|---|---|---|---|
| **Top-Down Retro Interior** | **Graphics created by Penzilla Design** (PenzillaDesign.com) | Prologue walls, floors, door, window, wood stove, table, pot rack, teapot, cup, pot, clock, candle; factory floor and grates | `interior/retro_*.png` |
| **Steampunk HP Bars** | mental.bloxx (Instagram @mental.bloxx) | Tinker's health gauge | `ui/hpbar_full.png`, `ui/hpbar_empty.png` |
| **Free Ambient Effects** | SovDigital (sovdigital.itch.io) | Steam, smoke, sparks, embers, dust and light shafts | `fx/*.png` |
| **Old House tile set** | *author not recorded in the pack, please add* | Prologue wallpaper, workbench, counter, chair, bucket, crates, rug, wall pipe | `interior/old_house_*.png` |
| **Junkyard_1** | *author not recorded in the pack, please add* | Junk piles, oil drums (hazard drums), crates | `props/junkyard.png` |
| **Animated Gears** (set 8) | *author not recorded in the pack, please add* | Spinning wall gears | `gears/gear_*.png` (every 10th frame) |

### Changes to the original files

The image files in `art/` are unmodified copies from the packs (only renamed, and only the
frames the game uses). At runtime the game:

- cuts individual sprites out of the sheets and scales them 2x with nearest-neighbour sampling;
- resamples the Junkyard_1 props and Animated Gears frames onto a 2px pixel grid;
- tints floors, walls and props darker for night scenes;
- paints a yellow-and-black hazard band onto the Junkyard_1 oil drum.

Penzilla Design's licence asks that public projects send a link to PenzillaDesign@gmail.com.
