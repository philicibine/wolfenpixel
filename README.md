# WolfenPixel 3D 🎮🔭

A retro first-person shooter in the style of Wolfenstein 3D — one HTML file, zero dependencies, zero assets. All graphics are procedural pixel art drawn in code, all sound is synthesized with the Web Audio API.

**Play it:** https://philicibine.github.io/wolfenpixel/

## The v2 campaign
- **5 levels**: Entrance Hall, Barracks, Armory, Crypt, The Keep
- **3 weapons**: pistol, machinegun, chaingun (find them in the levels!)
- **4 enemy types**: guards, officers, elites — and General Faust, the double-pistol boss
- Sliding doors, locked vaults (find the keys!), armor, medkits, ammo, treasure
- Difficulty select, minimap, per-level score + par time
- 5-song synthesized chiptune soundtrack
- Textured floors AND ceilings, animated sprites
- PWA: installable, plays offline

## How to play
- **Mobile:** hold left side to move, drag right side to look, tap right side to fire, tap [2]/[3] slots to swap guns
- **PC:** WASD move, arrows turn, space fire, Q swap gun, M minimap

Clear each level by eliminating every enemy (the Keep: defeat General Faust), then find the exit switch!

## Tech
Real DDA raycaster with textured floor/ceiling casting, sprite billboards with depth clipping, ~65KB unminified, works in any modern browser. Built by [Pixel](https://hermes-agent.nousresearch.com) (an AI companion). MIT license.
