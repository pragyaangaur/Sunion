# SUNION

**The Sun has layers. Like an onion. Let's peel it.**

An interactive explainer for the seven layers of the Sun. Built for anyone who has ever looked at a textbook diagram of the Sun and felt absolutely nothing.

---

## What's in it

**Peel It** — A clickable cross-section. Pick any of the seven layers and get its temperature, density, thickness, how humans actually observe it, and one fact designed to ruin your composure (the core generates less heat per cubic metre than a compost heap).

**Drill to the Core** — An impossible elevator. Drag from the centre of the Sun out through the corona and watch live temperature and density readouts interpolated from a simplified standard solar model. This is where the Sun's weirdest trick shows up: past the surface, the temperature *stops falling and starts climbing again*, from 4,100 °C to over a million. Nobody is entirely sure why. It's called the coronal heating problem.

**Quiz Me** — Seven questions with explanations, and a rank at the end ranging from *Total Eclipse* to *Solar Physicist*.

## A Note on Accuracy

The layer facts and the temperature/density profile are standard heliophysics ballpark figures (see [NASA: The Sun](https://science.nasa.gov/sun/)). They're right enough to learn from and be amazed by, and nowhere near precise enough to fly a spacecraft with.

Two deliberate distortions, both flagged in the UI:

- **The cross-section is schematic.** At true scale the photosphere would be a hairline and the transition region would be invisible — roughly one screen pixel. Thin layers are drawn thick enough to click.
- **The drill slider is non-linear.** It spends 60% of its travel on the interior, then stretches the wafer-thin atmosphere (1.00–1.04 R☉) across the next 25%, because that's where all the interesting physics is hiding.

Distances are reported in true solar radii (R☉ = 696,000 km) throughout, so you can always see the real proportions in the readout.

## Ideas if you want to fork it

- A "photon's journey" mode that random-walks a particle out of the radiative zone
- Compare mode: the Sun vs. a red dwarf vs. a red giant
- Swap in real SDO imagery for each layer's observing wavelength
