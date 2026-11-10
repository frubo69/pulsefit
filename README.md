# PulseFit prototype · F28ED Group 33

Fictional gym information interface for a within-subjects usability study.

- **Condition A**: one scrolling page (About, Opening hours, Membership, Facilities, Classes, Contact).
- **Condition B**: dashboard with four task cards; each opens a detail screen with a Back arrow.

Both conditions take their facts and wording from one list in `index.html`, so they cannot differ.

## Links

- `./` researcher setup (participant ID, start A or B)
- `./?c=a` condition A directly
- `./?c=b` condition B directly
- `./a/` and `./b/` short links for the QR codes: they open the Figma prototypes of A and B (participants use these)

The browser Back button goes from a condition back to the setup screen (in B: detail → dashboard → setup). Reloading keeps the current screen.

## At the stand

- Hold the **PulseFit** logo for about 1 second, or tap it three times, to open the researcher panel: task time, taps, scroll gestures, save / next task, switch condition, new participant, export CSV.
- Reset for a new participant: panel → **New participant**.
- After the first visit the prototype works without internet. On a phone, *Add to Home Screen* opens it full screen with no address bar.
- The log stays on the device only (participant IDs, no names). Export it as CSV at the end of each session.
