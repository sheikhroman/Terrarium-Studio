# 🌿 Verdant Glass — Interactive Terrarium Studio

**Verdant Glass** is a browser-based, tactile digital terrarium builder designed and developed from scratch without external frameworks or asset libraries. It combines custom vector botanical illustrations, procedural canvas/SVG rendering, real-time substrate layering, and synthesized Web Audio soundscapes into a cohesive UI/UX experience.

🔗 **[Live Demo](https://sheikhroman.github.io/Terrarium-Studio/)** 

---

## ✨ Key Features

- **🏺 Artisanal Glass Vessels:** Choose between 4 distinct custom-clipped SVG containers (*Classic Mason Jar*, *Geometric Wardian Case*, *Hanging Tear Globe* with physics sway, and *Apothecary Carboy*) with toggleable cork stoppers and multi-layered specular glass reflections.
- **🪨 Dynamic Substrate Engine:** Real-time millimeter depth control for *River Pebbles*, *Activated Charcoal*, *Organic Potting Soil*, *Golden Desert Sand*, and *Sheet Sphagnum Moss*. Placed botanicals automatically recalculate their vertical anchor points as soil contours change.
- **🌱 Custom Vector Flora & Hardscape:** 16+ bespoke SVG assets including *Boston Fern*, *Blue Echeveria*, *Pink Fittonia*, *Bioluminescent Toadstools*, *Amethyst Clusters*, and *Miniature Stone Lanterns*.
- **🎛️ Direct Canvas Manipulation:** Full pointer/touch drag-and-drop workflow with an integrated floating inspector for scaling, rotation, horizontal flipping, and z-index layer ordering.
- **🌙 Atmospheric Lighting & Biome FX:** Switch seamlessly between *Sunlit Day*, *Fairy Glow*, and *Bioluminescent Midnight* modes. Includes an interactive water mister (generating condensation droplets on the glass) and autonomous animated creatures (*Ladybug*, *Morpho Butterfly*, *Fireflies*).
- **🔊 Procedural Web Audio Synthesizer:** Zero external MP3 dependencies. Every interaction—soil pouring, water misting, glass tapping, and ambient night crickets—is synthesized in real time using the native Web Audio API.

---

## 🛠️ Tech Stack & Architecture

- **Core:** HTML5, CSS3 (Custom Properties, Grid/Flexbox, Backdrop Filters), Vanilla JavaScript (ES6+)
- **Graphics & Rendering:** Inline SVG with dynamic `<clipPath>` masking, `<feTurbulence>` procedural noise textures, and radial lighting gradients.
- **Audio Engine:** Native `AudioContext` API using custom oscillator envelopes and filtered white/pink noise buffers.
- **Persistence:** State serialization with `localStorage` auto-save and snapshot export capability.

---

## 🚀 Getting Started

Since this project is built with a zero-dependency architecture, no build steps or package managers are required.

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/sheikhroman/verdant-glass.git](https://github.com/sheikhroman/verdant-glass.git)
