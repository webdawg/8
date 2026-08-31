# 8

A self-contained, single-file HTML/canvas visualization called **Dark Matter Manifolds** — two calculus manifolds that can never touch, separated by a layer of dark matter, built up interactively over many rounds of iteration.

## View it

Open `dark-matter-manifolds.html` directly in a browser. No build step, no server, no dependencies — everything (HTML, CSS, JS) lives in that one file.

## What's on screen

Full definitions of every element (Left/Right Manifold, the Ribbon Leg Field, the Contour Flow, Dark Matter, the Afterbang Drips, the Tunnel and its Openings, the Dark Matter Chains, coupling forces, Scene Rotation, Entanglement) are documented in [GLOSSARY.md](GLOSSARY.md), each traced back to the original prompt that defined it.

## Controls

- **Drag the left or right half of the screen** — kicks that field with a damped-spring impulse; the two fields are coupled, so dragging one visibly affects the other.
- **Drag the middle (the gap)** — orbits the whole 3D tableau (both Manifolds and the Tunnel) freely on any axis.
- **+ / − buttons, top right** — zoom the camera in and out.

## Versioning

Every finalized checkpoint is archived as a standalone snapshot under [`archive/`](archive/) (`vN-dark-matter-manifolds.html`) and tagged in git (`vN`), so the full evolution of the piece is browsable without digging through commit history.

## Prompt log

Every prompt that shaped this project is logged verbatim under [`llm-original-prompt/`](llm-original-prompt/), one file per prompt, in order.

## License

Licensed under the GNU Affero General Public License v3.0 — see [LICENSE](LICENSE).
