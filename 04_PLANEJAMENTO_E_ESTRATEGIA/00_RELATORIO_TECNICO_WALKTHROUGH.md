# Walkthrough: JSG® Construction Limited — Behance Visual Brand Guide & Exact Vector System

## 1. Executive Summary & Objective

In accordance with direct feedback:
> *"brandguide, muito texto pouca imagem ele deve ser bonito igual o que falamos ta ruim assim"*  
> *"o logo nao ta batendo com o elemento precisa ajustar"*  
> *"não pode confundir os elementos temos um elemento nosso do logo manter o JSG com o r de registrado como fizemos nos primeiros"*  
> *"vamos fazer o brandguide dele igual o da quartile com tudo que eles tem la para apresentar para o sério faz versão em ingles e portugues"*

The entire Brand Guide has been rebuilt from the ground up as a **Behance-standard, edge-to-edge, visual-first presentation suite** modeled directly on high-end architectural monographs (such as *QUARTER*).

---

## 2. Key Architecture & Visual Upgrades

### A. Mathematical Vector Extraction of the True Proprietary Logo
- **Contour Extraction**: Extracted the exact modular geometry directly from the user's approved emblem (`logo_symbol_orange.png` / `media_1789320404296.png`) via OpenCV.
- **Lossless SVG Asset**: Generated `logo_exact_vector.svg` (`viewBox="0 0 100 100"`) featuring the signature negative-space 'S' channel, R12.5 tangent fillets, and modular blocks.
- **Strict Brand Protection**: Removed all AI-hallucinated hexagonal icons, mismatched outlines, and incorrect fonts. Only the official modular mark is utilized across the entire identity.
- **Mandatory Trademark Notation**: Applied **`JSG®`** (`U+00AE` / `&reg;`) with the registered trademark symbol across all corporate lockups, mockups, and legal headers.

### B. The 12 Edge-to-Edge Architectural Presentation Boards (1600×900px)
The presentation is structured as 12 full-bleed, agency-grade presentation boards:

1. **Board 01: Hero Cover & Identity Monograph** (`board_01_hero_cover.jpg`)
   - Heroic glowing vector monogram on CAD construction grid with Swiss modernist typography, Director Sérgio Gratival credits, and BEMKT agency imprint.
2. **Board 02: Monogram CAD Blueprint & Geometric Construction** (`board_02_monogram_cad.jpg`)
   - 100u modular matrix, tangent radii specifications, negative space load channel, and 1.5× clearspace boundaries.
3. **Board 03: Corporate Identity Matrix & Contrast Surfaces** (`board_03_logo_matrix.jpg`)
   - 4-up configuration: Primary Signal Orange on Obsidian, Monochrome Reversed White, Tactile Black on Concrete, and Horizontal Registered Corporate Lockup `[Monogram] JSG® CONSTRUCTION LTD`.
4. **Board 04: Chromatic System & Materiality** (`board_04_color_palette.jpg`)
   - 5 full-height architectural color columns calibrated with RAL, Pantone, CMYK, and RGB values:
     - RAL 2004 Signal Orange (`#FF5500`, Pantone 021 C)
     - RAL 9005 Obsidian Black (`#080A0D`, Pantone Black 6 C)
     - RAL 7016 Zinc Slate (`#10131A`, Pantone 433 C)
     - RAL 9002 Cast Concrete (`#EBEBEB`, Pantone Cool Gray 1 C)
     - RAL 7040 Technical CAD (`#8B949E`, Pantone Cool Gray 7 C)
5. **Board 05: Typographic Hierarchy Specimen** (`board_05_typography_specimen.jpg`)
   - Dual typeface structure: **Plus Jakarta Sans** (hero titles & editorial) + **Space Mono** (technical drawings, BCAR S.I. 9 schedules, telemetry HUDs).
6. **Board 06: Corporate Stationery & Luxury Collateral** (`board_06_stationery.jpg`)
   - Duplex 600gsm charcoal business cards with blind-debossed monogram and fluorescent orange painted edges, metallic silver foil-stamped presentation folder, solid brass drafting pencil, and RIAI contract documentation binder.
7. **Board 07: Site Hoarding & Perimeter Signage** (`board_07_site_hoarding.jpg`)
   - 12-metre modular site hoarding installed on a Dublin Georgian residential site with JCB excavator and brick townhouses. Exact orange vector monogram on vertical panel and `JSG® CONSTRUCTION LIMITED` with registered trademark.
8. **Board 08: High-Visibility PPE & Field Workwear** (`board_08_ppe_workwear.jpg`)
   - EN ISO 20471 Class 3 softshell technical jacket with embroidered rectangular chest patch (`JSG® CONSTRUCTION DUBLIN // 2026`), matte black helmet with reflective orange monogram and `JSG® CONSTRUCTION LIMITED`, and heavy-duty leather field gloves.
9. **Board 09: Commercial Fleet Vehicle Livery** (`board_09_fleet_van.jpg`)
   - Matte graphite Mercedes-Benz Sprinter van in Dublin. Inpainted body panels featuring our exact Signal Orange modular monogram, `JSG® CONSTRUCTION LIMITED`, and 3M safety chevrons.
10. **Board 10: Architectural Laser-Cut Metal Signage** (`board_10_laser_signage.jpg`)
    - 10mm anodized black aluminium architectural plaque with precision laser-cut monogram, 3000K warm LED halo backlighting, mounted on fair-faced concrete with 4 brushed standoffs.
11. **Board 11: Digital Ecosystem & Responsive Mobile Portal** (`board_11_digital_system.jpg`)
    - High-performance desktop browser & mobile UI preview highlighting portfolio galleries, cost calculator, and WCAG 2.1 AAA compliance.
12. **Board 12: Official Brand Governance & BEMKT Seal of Authenticity** (`board_12_brand_governance.jpg`)
    - Official certification signed off by Managing Director Sérgio Gratival and BEMKT Brand Architecture.

---

## 3. Interactive Features in `brandguide.html`

- **Instant Bilingual Switcher `[ 🇬🇧 EN | 🇧🇷 PT ]`**:
  - Live toggling of all chapter titles, metadata tags, and architectural descriptions without reloading the page.
- **Top Sticky Navigation Bar**:
  - Quick-jump navigation to all 12 boards (`01 Cover`, `02 CAD`, `03 Matrix`, `04 Color`, `05 Type`, `06 Stationery`, `07 Hoarding`, `08 PPE`, `09 Fleet`, `10 Signage`, `11 Digital`, `12 Seal`).
- **Interactive Lightbox Modal**:
  - Click any presentation board to open it in an ultra-crisp fullscreen viewer with keyboard support (`ESC` to close).
- **Interactive Color Swatches**:
  - One-click copy for Hex codes, RAL standards, and Pantone references with instant toast notifications.
- **Master Vector Assets Section**:
  - Direct download button for `logo_exact_vector.svg` and one-click "Copy SVG Code" button.
- **Print & PDF Export Engine**:
  - Optimized print stylesheet for generating clean client presentation PDFs.

---

## 4. Verification & Testing

- Automated Playwright browser tests executed at `http://localhost:8080/brandguide.html`.
- Verified seamless image rendering across all 12 boards at 1600×900 resolution.
- Verified bilingual toggle state persistence via `localStorage`.
- Verified navigation anchors and link integration from `index.html`.
