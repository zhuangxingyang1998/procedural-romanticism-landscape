# Procedural Romanticism Landscape (1920×1080)

A self-contained, zero-dependency procedural 19th-century Romanticism alpine sunrise landscape rendered at exact **1920×1080** resolution using only **HTML5 `<canvas>` (WebGL2) and Vanilla JavaScript**.

Every pixel, 3D vertex, leaf silhouette, bark furrow, mossy boulder, lake caustic, and volumetric sunbeam is synthesized purely from mathematics and deterministic seeded noise — no external libraries, no SVG imports, and no image assets.

## Live Demo & Docs

- **GitHub Pages**: https://zhuangxingyang1998.github.io/procedural-romanticism-landscape/
- **整体实现方案与技术架构（中文详解）**: [ARCHITECTURE.md](ARCHITECTURE.md)

## Features

- **Deterministic Seeded PRNG (`Mulberry32`)**: Reproducible terrain, fractal trees, boulders, clouds, and wildflower layouts for any numeric or string seed (default hero seed: `1874`).
- **Atmospheric Sky & Raymarched Alpine Peaks**: Rayleigh/Mie-inspired sunrise gradients, domain-warped clouds, and 120-step raymarched ridged-multifractal mountains with self-shadowing and distance valley mist.
- **Procedural Fractal Forest & 43,000+ Instanced Leaves**: Recursive gnarled ancient broadleaf trees and alpine pines with root flares, parallel-transport tubular trunks, procedural leaf-vein / needle-spray textures, canopy ambient occlusion, and backlit subsurface scattering.
- **Physically-Inspired Alpine Lake**: Perspective-accurate planar reflection combined with Schlick Fresnel, depth-based Beer-Lambert water clarity revealing submerged pebbles/boulders and animated Voronoi caustics, plus non-repeating multi-directional micro-ripples.
- **Volumetric God Rays & Particle Atmosphere**: 56-tap radial volumetric light shafts piercing through canopy and valley gaps, swaying shoreline ferns, bioluminescent wildflowers, 1,800 drifting dust/spore/mist particles, separable HDR bloom, and ACES Filmic tone mapping.

## Local Usage

Open `index.html` directly in any modern WebGL2-capable browser (works 100% offline).

### Controls
- **Look Around**: Left-click & drag on the canvas.
- **Move / Fly**: `W` `A` `S` `D` or Arrow keys to move horizontally, `Q` / `E` (or `C` / `Space`) to descend / ascend, hold `Shift` to fly faster, mouse wheel to dolly forward/backward.
- **Reset Camera**: Press `R` or click **重置视角 (R)**.
- **Seed**: Enter any seed and click **生成** (or press `Enter`), or click **随机种子** for a new composition.
- **Pause / Play**: Toggle subtle real-time micro-motion.
- **Export PNG**: Save an exact `1920×1080` PNG snapshot.
- **`H` Key**: Show/hide the floating HUD overlay.
