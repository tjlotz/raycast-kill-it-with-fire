# Raycast Fire
Kill it with fire! Set your screen on fire and watch it burn. A chaotic alternative to Raycast's confetti. 

## Why
Raycast has confetti. That's nice. 

This does the opposite for when you need to kill something with fire.

## Features
- Full-screen flame animation that grows from the bottom to midscreen
- Smoke rises from the flame front to the top of the viewport
- Lightweight canvas particle system — zero dependencies
- Click or use the **Ignite!** button to trigger the effect

## Project Structure

```
├── index.html          Entry point (open in browser)
├── package.json        npm metadata & convenience scripts
├── README.md
└── src/
    ├── script.js       Particle engine, emitters, animation loop
    └── style.css       Layout & control-button styles
```

## Getting Started

Open `index.html` directly in a browser, or run a local server:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Controls

| Action | Effect |
|--------|--------|
| **Ignite!** button | Triggers a full-width growing flame (~3 s) |
| **Stop** button | Clears all particles and stops animation |
| Click anywhere | Same as **Ignite!** |

## Next Steps

- Tune particle colours, spawn patterns, and blur for a more convincing flame.
- Port the canvas into a Raycast extension UI component and wire up a command.