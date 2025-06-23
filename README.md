# Jesu, Joy of Man's Desiring – Organ Performance

A web-based, interactive pipe organ simulation of Bach's **"Jesu, Joy of Man's Desiring"** (BWV 147).

**Live Demo:**  
[isaka-james.github.io/bach/](https://isaka-james.github.io/bach/)

---

## Features

- **Authentic pipe organ sound** using the Web Audio API
- Animated organ pipes and sound wave visualizer
- Play and Stop controls (stop button only visible during playback)
- Responsive design for desktop and mobile
- No music loops: the piece plays once per click

## Usage

1. **Visit:** [isaka-james.github.io/bach/](https://isaka-james.github.io/bach/)
2. Click **"▶ Play Performance"** to start the organ.
3. Click **"⏹ Stop"** to halt playback and reset the visualizer.

## Project Structure

- `index.html` – Main app, UI, and all JavaScript logic
- No dependencies, no build step required

## Customization

- To change the music or organ sound, edit the `melody` and `pedalBass` arrays in `index.html`.
- Visual and audio logic is fully contained in the HTML file.

## License

MIT License

---