# HTML5 Canvas Fireworks Simulation

This project is a highly detailed, realistic fireworks simulation built using HTML5 Canvas, JavaScript, and the Web Audio API. 

## Features

- **Realistic Physics Engine:** Simulates gravity, air drag, and particle speed to create lifelike firework bursts and trails.
- **Multiple Firework Types:** Includes a wide variety of shell effects such as Crysanthemum, Ghost, Strobe, Palm, Ring, Crossette, Floral, Falling Leaves, Willow, Crackle, and Horse Tail.
- **Choreographed Sequences:** When Auto Fire is enabled, fireworks are launched in pre-programmed patterns and sequences (e.g., Pyramids, Barrages).
- **Dynamic Audio:** Uses `AudioContext` to play dynamic lifelike sound effects (`lift`, `burst`, `crackle`) based on shell size and timing.
- **Customizable Settings:** You can easily configure the simulation settings, including:
  - Graphics Quality (Low, Normal, High)
  - Shell Size (3" to 16")
  - Sky Lighting Intensity
  - Scale Factor
  - Auto Fire / Finale Mode

## Files

- **`index.html`**: The main webpage structure containing the canvas element and the UI overlays.
- **`style.css`**: The styles for the UI, menus, and canvas layout.
- **`main.js`**: The core simulation engine that drives the physics, rendering, sequences, and audio.

## Usage

Simply open `index.html` in any modern web browser to start the simulation. 
- You can tap or click anywhere on the screen to manually launch a firework.
- Click the top right corner to open the settings menu and tweak the simulation properties.
