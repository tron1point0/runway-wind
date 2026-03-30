# Runway Wind Calculator

Offline-capable runway crosswind and headwind calculator for pilots.

## Usage

Open `index.html` in any browser. No server required for local use.

For offline/PWA installation on mobile:
```bash
python3 -m http.server 8080
```
Then open `http://<your-ip>:8080` on your phone and add to home screen.

## Features

- Draggable runway on compass rose (snaps to 10° increments)
- Draggable wind direction (1° precision)
- Wind speed slider (0-30 kt)
- Dynamic headwind/tailwind and crosswind calculations
- Responsive layout (portrait and landscape)
- Works fully offline

## Controls

- **Drag runway** - rotate to set landing direction
- **Click runway** - flip to opposite direction
- **Drag wind arrow** - set wind direction
- **Slider** - set wind speed
