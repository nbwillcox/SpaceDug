# SpaceDug

A free, retro-flavored underground mining arcade game with modern neon graphics and a head nod to classic dig-and-pump arcade games. Tunnel through layered asteroid rock hunting rare minerals, inflate hostile aliens until they pop, and drop boulders on the rest.

**Play it in your browser:** https://nbwillcox.github.io/SpaceDug/

Everything is generated in code: sprites are vector-drawn on the fly, and all sound effects and music are synthesized with the Web Audio API. There are no image or audio files and no build step. A sibling of [SpaceGalaShooter](https://github.com/nbwillcox/SpaceGalaShooter), [SpaceCentiShooter](https://github.com/nbwillcox/SpaceCentiShooter), [SpaceVaderShooter](https://github.com/nbwillcox/SpaceVaderShooter), [SpaceStroids](https://github.com/nbwillcox/SpaceStroids), [SpaceCommand](https://github.com/nbwillcox/SpaceCommand), [lightCycles](https://github.com/nbwillcox/lightCycles), [SpaceRoboShooter](https://github.com/nbwillcox/SpaceRoboShooter), [SpaceBricks](https://github.com/nbwillcox/SpaceBricks), [SpaceSidePews](https://github.com/nbwillcox/SpaceSidePews) and [SpaceFrogger](https://github.com/nbwillcox/SpaceFrogger), with the same look and feel.

## Controls

| Action | Keys |
| --- | --- |
| Move and dig in any direction | Arrow keys or `W` `A` `S` `D` |
| Fire the pump hose, then hold to inflate | Hold `Space` (or left mouse button) |
| Pause | `P` or `Esc` |

Desktop browsers with a keyboard only for now.

## Gameplay

- **The goal:** every level hides rare minerals in the rock. Find enough of them to meet the quota and the extraction hatch opens: climb back to the surface to finish the level. Or pop every alien and clear the level that way.
- **Minerals** are buried with only a faint glint to give them away. The deeper the layer, the rarer the mineral: Ferrite, Aurelium, Nebulite and a single super-rare Quasarite per level (worth two toward the quota).
- **The pump:** aim at an alien in a straight tunnel and hold `Space`. The hose latches on and each pump inflates it a stage; four pumps and it pops. Let go and it deflates and comes back for you. Inflated aliens can't hurt you, but anything else that touches you can.
- **Aliens:** Blobs chase you through your tunnels and turn into ghosts to cut straight through rock. Drakes breathe a line of fire. From later levels, Burrowers dig their own tunnels and Spitters shoot along open lines.
- **Boulders:** dig out the rock under a boulder and it drops, crushing whatever is below (an alien, or you). Crushing several aliens at once scores big, and every second boulder you drop leaves a bonus crate.
- **Hazards:** glowing lava seams are deadly to touch, and green gas pockets burst into a lethal cloud when you dig them open. Lure aliens into it.
- **Crates buried in the rock:** drill boost (dig faster), long hose (longer reach and faster pumping), a one-hit shield and a scanner that reveals nearby minerals.
- **Bosses:** every 5th level the Alien Queen waits in a big cavern. Pump her up, or drop the boulders hanging above her cavern.
- Endless levels with rising difficulty, extra lives at 20,000 and 60,000 points, and local top-10 high scores with arcade-style 3-letter initials (stored in your browser).

## Run locally

It is plain HTML/CSS/JS. Either open `index.html` directly, or serve the folder:

```bash
python -m http.server 8000
```

then visit http://localhost:8000.

## License and attribution

Licensed under [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/): free to play, share and remix **non-commercially**, as long as you give credit and **link back to this repository**: https://github.com/nbwillcox/SpaceDug

This is an original game inspired by classic arcade games. It uses no assets, names or code from any existing game.
