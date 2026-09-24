# Circole — Number Label Maker

**Circole** is a modern, client-side web application designed for creating custom number labels, transit/route markers, and batch sheet printing.

## Features

- **Custom Geometry:** Switch between circle and rounded rectangular bases with customizable dimensions and corner roundness.
- **Color & Effects:** Solid or gradient fills, customizable opacities, and independent Gaussian drop shadows for both shapes and text.
- **Paper & Batch Mode:** Print single labels or multi-cell grids on A4 / US Letter sheets in Portrait or Landscape orientations.
- **Vector Path Export:** Uses OpenType.js to convert text glyphs directly into pure SVG `<path>` vectors, avoiding font fallback bugs and preserving full styling in editors like Adobe Illustrator and Figma.
- **Cross-Platform Fonts:** Built-in web fonts via Fontsource CDN, custom font uploading (TTF, OTF, WOFF), and local font scanning via the Local Font Access API (Chromium desktop).
- **Settings Persistence:** Save and reload custom configurations as `.circole` JSON files.
- **Multilingual:** Full support for English and Spanish.

## Getting Started

Because Circole is a standalone client-side application, no build steps, bundlers, or servers are required.

1. Clone the repository:
   ```bash
   git clone [https://github.com/](https://github.com/)<your-username>/circole.git
