# HALCYRA VX-4: a robotic camera drone you can take apart

A concept drone rebuilt from one reference image, entirely in code, with three.js. Take the canopy off, blow it apart, spin up the rotors.

**Live page:** https://lein5in.github.io/halcyra-vx4/

## What you can do
- Drag (or one finger) to orbit, wheel or pinch to zoom, double-click or double-tap to reset the view.
- Buttons: CANOPY, EXPLODE, ASSEMBLE, FLY OUT. Sliders: EXPLODE, THROTTLE, GIMBAL.
- Leave it alone and it tours itself. Touch anything and it hands you control; it takes it back after 25 s of quiet.
- Keys: Space tour on/off, 1-4 the four buttons, R reset, F fullscreen, H hide the panels.

## How it is made
One object, modelled entirely in code. The readouts (rotor speed and thrust, battery, gimbal tilt) are computed from the same state that poses the drone. Mass, battery and power figures are invented for the concept. The page is a single offline HTML file.

## Concept only
HALCYRA VX-4 is an invented product name. This is not a real product.

## Credits
- Method and kit: [Nyxera0x/cutaway](https://github.com/Nyxera0x/cutaway) (MIT), built on [whaleyxbt/claude-motion](https://github.com/whaleyxbt/claude-motion) (MIT)
- Live page structure: [elvarofficial/teardown](https://github.com/elvarofficial/teardown) (MIT)
- three.js (MIT); Inter and JetBrains Mono fonts (SIL OFL)


## Licence
MIT, see LICENSE.