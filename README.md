# GSAP Spotlight — Dithered

An interactive spotlight reveal built with GSAP. Move the pointer (or drag a finger) to illuminate the artwork. A WebGL post-process re-renders the scene with 3px Bayer ordered dithering, using a palette sampled from the image.

- Single self-contained `index.html` (the image is embedded), so it works opened directly, on Netlify, CodePen, or as a Framer embed.
- `bg.jpg` is the source image used for the embedded copy.

## Run locally

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000.
