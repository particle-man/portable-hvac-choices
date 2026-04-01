# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Purpose

This repository is a knowledge base for portable AC unit selection. It contains:

- **Decision matrix**: A markdown table comparing portable AC units across key criteria (BTU, efficiency, noise, price, form factor, etc.)
- **3D printer models**: STL/CAD files for physical modifications and adapters (exhaust adapters, window kits, mounting brackets, etc.)

## Repository Structure

```
docs/
  decision-matrix.md   # Main comparison table with purchase links, specs, conversion evidence
assets/
  3d-models/
    INDEX.md           # Catalogue of 3D-printable dual-hose conversion parts (links to Printables/Thingiverse/MakerWorld)
```

## Key Context

- All portable ACs sold new in the UK are single-hose. This repo tracks units that can be **converted to dual-hose** via 3D-printed adapters or DIY mods.
- Every unit in the decision matrix must have: a verified UK purchase link, noise specs (dBA), and a reference proving dual-hose conversion is possible (3D model, guide, or community post).
- 3D model STL files are hosted externally (Printables, Thingiverse, MakerWorld). `assets/3d-models/INDEX.md` indexes them with download links, compatibility notes, and print settings.

## Conventions

- Decision matrix lives in markdown for diffability and easy review
- Noise values are reported as dB(A) range (operating min – max)
- Prices are in GBP (£) and should be updated periodically with current retailer links
- 3D model entries must include: source link, compatible AC model(s), hose diameter, and print notes
- Use millimeters for all 3D model measurements
- Keep image assets reasonably sized (compress PNGs, use JPEG for photos)
