# Cyclomente

Cyclomente is a simple synthesizer created in [Max 8](https://cycling74.com/) to explore the possibilities of the [Buchla Thunder Overlay](https://sensel.com/blogs/news/buchla-announcement) for Sensel Morph.

The synthesizer consists of two copies of a simple additive oscillator, each with its own modulation oscillator (similar to classic "west coast" complex oscillator designs). The controls for each oscillator are represented by the left and right sides of the overlay interface.

Pressure and position on each of the main finger pads will control the amplitude and modulation amount of its respective harmonic partial, while the hexagonal pads control modulation frequency and overall modulation amount for their respective oscillator. The numbered pads across the top will set the fundamental frequency to one of four preset pitches.

## Installation:

- Clone or download this repo
- Open the Sensel app and import `Cyclomente.senselmap` into your Thunder overlay
- Open `Cyclomente.maxpat` in Max, select the Sensel Morph from the `midiin` object, and enable the DAC
- Enjoy :)
