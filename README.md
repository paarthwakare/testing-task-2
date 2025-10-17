# Overview
This web app renders a 3D Earth rotating on its axis, complete with:
- Realistic surface texture, normal and specular maps
- Semi-transparent, drifting cloud layer
- Axial tilt of 23.5°
- Starfield background
- Interactive camera (drag to orbit, scroll/pinch to zoom)
- Controls to adjust rotation speed, pause/resume, and reset the view

Built with Three.js and publicly hosted textures.

# Setup
No build step required.

1. Save the provided index.html file.
2. Open index.html in any modern browser with WebGL support (Chrome, Edge, Firefox, Safari).

Internet access is required to fetch Three.js and textures from CDNs.

# Usage
- Drag to rotate the camera around Earth.
- Scroll (or pinch) to zoom.
- Rotation speed slider:
  - 0x to 3x relative to the default demo speed (one rotation in ~24 seconds at 1.0x).
- Pause/Resume to stop/start Earth rotation.
- Reset View to return the camera to the initial position.

If performance is slow on older devices:
- Reduce browser zoom or close other heavy tabs.
- Lower the page/device resolution (DPR).