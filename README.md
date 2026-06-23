# Ramin Rasulzade — Personal Website & Tech Art Showcase

Welcome to the repository for my personal portfolio and technical journal. This platform serves as a central hub for showcasing real-time graphics pipelines, shader implementation demos, and interactive 3D assets alongside an editorial log of my engineering processes.

Live Website: [raminrasulzade.com](https://raminrasulzade.com)

---

## 🎨 Dual Identity Philosophy

The core branding and architecture of this site are split down the middle to balance two distinct halves of my workflow:
* **The Creative Side:** Fluid, calligraphic layouts, and smooth animations highlighting custom VFX, procedural modeling layouts, and real-time aesthetic choices.
* **The Technical Side:** High-performance, monospaced data structures, and optimized layout architecture mirroring compiler logic and structured low-level graphics engines.

---

## 🛠️ Tech Stack & Architecture

This project is engineered for speed, high visual fidelity, and clean content editing without third-party overhead:

* **Framework:** [Astro v6](https://astro.build) — Configured for modern server-side rendering pipelines and ultra-fast compilation.
* **Style Engine:** [Tailwind CSS v4](https://tailwindcss.com) — Powered natively through Vite's fast compilation layers with zero old integration plugins.
* **3D Viewports:** Google `<model-viewer>` — Embedded lightweight canvas layers rendering high-fidelity interactive GLTF/GLB formats directly on the home dashboard.
* **Typography:** Tailwind Typography (`prose`) — Heavily tuned layout columns optimizing reading line lengths and deep neutral colors for text legibility.
* **Hosting Pipeline:** Cloudflare Pages — Built directly over a modern `wrangler` worker edge ecosystem tracking the `develop` development branch for atomic deployments.

---

## 🚀 Project Layout Directory

```text
├── public/                 # Static global assets (Custom favicons, 3D model .glb layers)
│   └── images/             # Root target images served directly to the browser
├── src/
│   ├── components/         # Modular building blocks (Sleek unified Header and Footer)
│   ├── content/            # Local content collections (Markdown and MDX journals)
│   ├── layouts/            # Master layout page grids (Highly readable article wrappers)
│   └── pages/              # Explicit application routing tree (Home, Blog, Portfolio)
├── astro.config.mjs         # Streamlined framework and edge adapter setup
├── package.json            # Strict dependency version controls
└── wrangler.jsonc          # Cloudflare configuration configuration layer