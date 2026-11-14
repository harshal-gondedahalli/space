# SPACE — Junior Astronaut Mission

A browser-based educational space project with two playable experiences.

## Play the games

### Rocket Builder & Space Voyage
Open [index.html](./index.html) to build a rocket, run a simulated launch, control a flight, choose a destination, and explore a planetary surface.

### Outpost Command — Mission Trainer
Open [outpost.html](./outpost.html) to manage a Moon or Mars outpost for 10 simulated sols. Balance power, life support, food production, and radiation shielding through choices with competing costs. The page can request recent space-weather notifications from NASA's DONKI API when online; if the service is unavailable, the simulation remains playable and clearly labels the feed as unavailable.

## Run online

Enable GitHub Pages:
1. Open **Settings → Pages**.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select branch **main** and folder **/(root)**, then Save.
4. Visit https://hrashal-gondedahalli.github.io/space/

Direct pages:
- Rocket Builder: https://hrashal-gondedahalli.github.io/space/
- Outpost Command: https://hrashal-gondedahalli.github.io/space/outpost.html

## Learning and data notes

Outpost Command uses simplified illustrative resource units and educational scenario outcomes. These are not real spacecraft operating limits, radiation-dose estimates, or medical safety thresholds. The optional space-weather request uses NASA's public DONKI API and identifies returned notifications as contextual information, not a personal radiation calculation.

Sources:
- NASA Open APIs: https://api.nasa.gov/
- NASA DONKI: https://ccmc.gsfc.nasa.gov/tools/DONKI/

All rocket launches, flight controls, and surface activities in the original game are simulations.
