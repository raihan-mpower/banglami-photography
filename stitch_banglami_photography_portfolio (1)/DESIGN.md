---
name: Terracotta & Archival Monolith
colors:
  surface: '#f8f9ff'
  surface-dim: '#d8dadf'
  surface-bright: '#f8f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f3f9'
  surface-container: '#eceef3'
  surface-container-high: '#e6e8ee'
  surface-container-highest: '#e1e2e8'
  on-surface: '#191c20'
  on-surface-variant: '#59413b'
  inverse-surface: '#2e3135'
  inverse-on-surface: '#eff0f6'
  outline: '#8d7169'
  outline-variant: '#e1bfb6'
  surface-tint: '#af300b'
  primary: '#a62a03'
  on-primary: '#ffffff'
  primary-container: '#c8421d'
  on-primary-container: '#fff3f0'
  inverse-primary: '#ffb4a1'
  secondary: '#ac3311'
  on-secondary: '#ffffff'
  secondary-container: '#ff6e48'
  on-secondary-container: '#651400'
  tertiary: '#69553a'
  on-tertiary: '#ffffff'
  tertiary-container: '#836d50'
  on-tertiary-container: '#fff4eb'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdbd1'
  primary-fixed-dim: '#ffb4a1'
  on-primary-fixed: '#3c0800'
  on-primary-fixed-variant: '#881f00'
  secondary-fixed: '#ffdbd1'
  secondary-fixed-dim: '#ffb4a1'
  on-secondary-fixed: '#3c0800'
  on-secondary-fixed-variant: '#881f00'
  tertiary-fixed: '#fbdebb'
  tertiary-fixed-dim: '#dec2a1'
  on-tertiary-fixed: '#271904'
  on-tertiary-fixed-variant: '#57432a'
  background: '#f8f9ff'
  on-background: '#191c20'
  surface-variant: '#e1e2e8'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 56px
    fontWeight: '600'
    lineHeight: 64px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 38px
    fontWeight: '600'
    lineHeight: 46px
    letterSpacing: -0.01em
  display-md:
    fontFamily: Playfair Display
    fontSize: 44px
    fontWeight: '500'
    lineHeight: 52px
    letterSpacing: -0.015em
  display-md-mobile:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '500'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '500'
    lineHeight: 40px
  headline-md:
    fontFamily: Playfair Display
    fontSize: 24px
    fontWeight: '500'
    lineHeight: 32px
  headline-sm:
    fontFamily: Playfair Display
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  body-lg:
    fontFamily: Manrope
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Manrope
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Manrope
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
  label-lg:
    fontFamily: Manrope
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.04em
  label-md:
    fontFamily: Manrope
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.06em
  label-sm:
    fontFamily: Manrope
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 14px
    letterSpacing: 0.08em
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 3rem
  margin-mobile: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.75rem
  space-xl: 3rem
---

## Brand & Style
The design system positions Banglami Photography as a high-end cultural archive and museum exhibition space. The visual narrative combines strict editorial minimalism with the tactile warmth of Bengal’s terracotta temples and patachitra scroll paintings. The atmosphere is quiet, contemplative, and authoritative—letting visual storytelling command full focus while functional UI operates with surgical restraint.

The style uses an **Editorial Minimalist** framework: pure gallery-white planes, structural rule lines, disciplined typography scales, and deliberate terracotta accents. It avoids synthetic gradients, heavy skeuomorphic effects, and decorative clutter, favoring generous negative space, intentional rhythm, and curatorial precision.

## Colors
The palette evokes archival gallery exhibition spaces and indigenous Bengal claycraft:
- **Canvas & Surface Base:** Pure gallery white (`#ffffff`) serves as the foundational wall plane. Secondary structural fills use subdued museum stone (`#f9fafb`) and light parchment borders (`#eaecef`, `#f3f4f6`).
- **Typography & Core Neutral:** Deep soot charcoal (`#111418`) delivers razor-sharp reading contrast for headlines, metadata, and prominent UI markers. Muted body and secondary captions lean on graphite (`#2a2d34` and `#525866`).
- **Accents:** Terracotta red (`#c8421d`) anchors primary calls to action, focal indicators, and exhibition dates, backed by warm saffron terracotta (`#d9532f`) for hover states and active indicators. Muted raw umber (`#8a7356`) provides subtle historical depth for category tags and index numbers.

## Typography
Typography balances museum curatorial classicism with modern editorial legibility:
- **Serif Lead (`Playfair Display`):** Reserved for exhibition titling, narrative collection intros, and display headings. It lends humanistic, literary gravitas that honors traditional Bengal printmaking and editorial documentation.
- **Sans-Serif Engine (`Manrope`):** Employed for body narrative, technical photographic metadata (shutter speed, medium, location, provenance), indices, and interactive controls. Its clean geometric precision keeps dense archival information effortless to scan.
- **Labels & Microcopy:** Rendered with tracked-out uppercase formatting (`letter-spacing: 0.06em` to `0.08em`) to mirror archival accession plates and white-cube museum placards.

## Layout & Spacing
The layout system treats the viewport as an exhibition space:
- **Grid Architecture:** Desktop displays run on a 12-column symmetrical grid with a maximum content container width of 1440px. Tablets shift to an 8-column layout with 1.5rem gutters, while mobile adapts to a single or 4-column flow with 1rem gutters and compact 1.25rem margins.
- **Museum Whitespace:** Generous vertical rhythm separates photographic bodies from curatorial commentary. Galleries alternate between full-bleed focus spreads and asymmetric, column-pinned images to evoke high-end editorial volumes.
- **Grid Alignment:** Architectural rule dividers (`1px solid #eaecef`) cleanly separate header mastheads, curated series, and footer cataloguing.

## Elevation & Depth
In keeping with clean museum aesthetics, physical drop shadows and glossy blurs are discarded in favor of:
- **Surface Planarity:** Visual separation is established strictly through pure `#ffffff` fields, soft stone sub-layers (`#f9fafb`), and hair-thin rule lines (`#eaecef`).
- **Low-Contrast Structural Borders:** Cards, metadata plaques, and photograph mounts rely exclusively on delicate 1px borders rather than elevation, keeping the photographic subject pure and unencumbered.
- **Curatorial Overlays:** For fullscreen photo viewers or lightbox views, use an opaque, solid soot scrim (`rgba(17, 20, 24, 0.94)`) with zero backdrop blur, ensuring high contrast against the image content.

## Shapes
The design adopts a strict **Sharp (`0px`)** geometry.
- Buttons, visual frames, exhibition cards, dropdowns, and form inputs utilize crisp, unrounded 90-degree corners.
- This architectural precision references photographic prints, slide mounts, museum display stands, and traditional print broadsides, reinforcing an uncompromising, high-end fine art presence.

## Components

### Buttons
- **Primary:** Solid terracotta (`#c8421d`) fill, `#ffffff` Manrope typography (`label-md`, uppercase), zero corner radius, 12px 24px padding. Hover transitions smoothly to saffron terracotta (`#d9532f`).
- **Secondary / Archival Outline:** 1px border in `#111418` over transparent background; text in `#111418`. Hover fills `#111418` with white text.
- **Ghost:** Text-only button with a 1px terracotta underline that animates outward on hover.

### Chips & Accession Tags
- Sharp rectangular capsules with a 1px border in `#eaecef`, background in pure `#ffffff`, text in `#2a2d34` Manrope (`label-sm`, uppercase).
- Active or filtered state switches border and text to `#c8421d` with an ivory-tinted fill (`#fdf7f5`).

### Photography Cards & Exhibition Tiles
- Borderless frame or delicate 1px `#eaecef` perimeter outline with zero rounding.
- Imagery is framed by generous negative space mimicking exhibition matboards.
- Metadata plaque sits immediately beneath the frame: title in Playfair Display (`headline-sm`), followed by medium, year, and region in Manrope (`label-sm`, `#525866`).

### Input Fields & Search
- Minimalist underline or 1px box format using `#eaecef` border, pure white interior, and `#111418` input text.
- Focus state transforms the border to `#c8421d` without outer glow. Floating placeholder in Manrope (`body-sm`).

### Checkboxes & Radio Controls
- Square 16px boxes with 1px border in `#111418`. Checked state renders a solid terracotta `#c8421d` inner fill or solid terracotta center square, retaining precise geometric angles.

### Curatorial Placards & Provenance Lists
- Structured two-column key-value list divided by 1px `#f3f4f6` borders.
- Keys (e.g., "LOCATION", "YEAR", "CURATOR") set in `label-sm` muted graphite; values set in `body-md` soot charcoal `#111418`.