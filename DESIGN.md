---
name: UTFRide Dynamic Transit
colors:
  surface: '#fbf8ff'
  surface-dim: '#dad9e3'
  surface-bright: '#fbf8ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f4f2fd'
  surface-container: '#eeedf7'
  surface-container-high: '#e8e7f1'
  surface-container-highest: '#e3e1ec'
  on-surface: '#1a1b22'
  on-surface-variant: '#4e4632'
  inverse-surface: '#2f3038'
  inverse-on-surface: '#f1effa'
  outline: '#80765f'
  outline-variant: '#d2c5ab'
  surface-tint: '#745b00'
  primary: '#745b00'
  on-primary: '#ffffff'
  primary-container: '#ffcc00'
  on-primary-container: '#6f5700'
  inverse-primary: '#f1c100'
  secondary: '#5f5e5e'
  on-secondary: '#ffffff'
  secondary-container: '#e5e2e1'
  on-secondary-container: '#656464'
  tertiary: '#5d5e60'
  on-tertiary: '#ffffff'
  tertiary-container: '#d2d2d3'
  on-tertiary-container: '#595a5b'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffe08b'
  primary-fixed-dim: '#f1c100'
  on-primary-fixed: '#241a00'
  on-primary-fixed-variant: '#584400'
  secondary-fixed: '#e5e2e1'
  secondary-fixed-dim: '#c8c6c5'
  on-secondary-fixed: '#1c1b1b'
  on-secondary-fixed-variant: '#474646'
  tertiary-fixed: '#e2e2e3'
  tertiary-fixed-dim: '#c6c6c7'
  on-tertiary-fixed: '#1a1c1d'
  on-tertiary-fixed-variant: '#454748'
  background: '#fbf8ff'
  on-background: '#1a1b22'
  surface-variant: '#e3e1ec'
typography:
  display-currency:
    fontFamily: Inter
    fontSize: 26px
    fontWeight: '700'
    lineHeight: 32px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
    letterSpacing: -0.015em
  headline-md:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '700'
    lineHeight: 28px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 24px
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '500'
    lineHeight: 24px
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  body-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
  label-lg:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.02em
  label-pill:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '700'
    lineHeight: 14px
    letterSpacing: 0.03em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1rem
  margin: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 0.75rem
  space-lg: 1rem
  space-xl: 1.5rem
---

## Brand & Style

The design system establishes a high-velocity, trusted, and utilitarian mobile-first environment tailored for university ride-sharing. It merges the punchy, high-visibility commercial mechanics of urban ride-hailing apps (such as 99 and Uber) with the authoritative civic identity of UTFPR.

### Aesthetic Tone & Visual Mood
- **Hyper-legible & High-Contrast:** Vibrant canary gold paired strictly against deep onyx creates instant visual anchors for actionable targets and rapid scanning on glare-heavy mobile screens.
- **Urban Utility:** No extraneous decorative flourishes. Functional components, direct spatial pathways, clear pricing highlights, and intuitive transit wayfinding dominate the viewport.
- **Safe & Communal Trust:** Clean white layered containers floating above neutral grey foundations communicate institutional safety, reliability, and modern academic camaraderie.
- **Movement & Tactility:** Micro-interactions emphasize quick touch feedback, responsive drag sheets, and immediate validation for booking, confirming, and navigating rides.

## Colors

The palette balances the institutional academic yellow of UTFPR with deep, saturated architectural tones. High contrast ratios (WCAG AAA for text, AA for visual indicators) ensure clarity outdoors under bright sunlight.

### Core Roles
- **Primary (`#FFCC00`):** The operational core. Used for primary CTAs, active route segments, pickup markers, and accent highlights. Always paired with `#111111` typography or icons for maximum legibility.
- **Secondary / Deep Surface (`#111111`):** Structural anchors, high-level headers, bottom navigation bars, and primary dark buttons.
- **Neutral Canvas (`#F4F4F5`):** Base canvas background, recessed search wrappers, segmented controls, and subtle container fills.
- **Supporting Neutral (`#71717A`):** Secondary metadata, route subtexts, university campus building tags, and divider outlines.
- **Surface Pure (`#FFFFFF`):** High-priority modular cards, dynamic bottom sheets, dialog modals, and input fields.

### Semantic Tones
- **Success (`#16A34A`):** Confirmed rides, driver arriving, and validated institutional ID badges.
- **Destructive (`#DC2626`):** Ride cancellations, report student driver, seat unavailability, and session termination.
- **Warning / Pending (`#D97706`):** Seat reservation pending confirmation, matching driver, and traffic delays.

## Typography

Typographic scale is constructed with **Inter** for clean glyph shapes, balanced numerals, and immediate legibility on handheld devices.

- **Monetary Distinction (`display-currency`):** Values in `R$` are rendered in `26px` bold with condensed tracking (`-0.02em`), emphasizing the student cost-split directly against card headers.
- **Headers & Headings:** `headline-md` (`20px`) and `headline-lg` (`24px`) serve as anchors on bottom-sheet headers and ride-detail summaries.
- **Micro-labels (`label-pill`):** Compact, uppercase-optional `11px` bold treatments for quick badge scans: campus markers (e.g., "CÂMPUS ECOVILLE", "SEDE NEOPIRAPORA"), vehicle tags, and seat counts.
- **Tabular Figures:** All transit timestamps, seat counts, and price calculations must utilize OpenType tabular numbers (`tnum`) to eliminate layout jitter during dynamic updates.

## Layout & Spacing

The layout operates on a compact 4px baseline rhythm optimized for one-handed mobile ergonomic zones.

### Breakpoints & Adaptive Matrix
- **Mobile First (0 - 599px):** Full-bleed maps with floating utility headers, dynamic draggable bottom sheets anchoring interactive workflows, and a fixed 4-tab bottom navigation rail (56px tall + safe area). Standard margins sit strictly at `16px` (`margin: 1rem`).
- **Tablet / Responsive PWA Container (600px+):** Centers the application within a constrained phone shell (`max-width: 480px`) or expands to a split view (left: navigation & route list, right: map view).

### Spatial Hierarchy
- **Touch Targets:** Minimum interactive touch bounding box is `48px × 48px`. Core primary triggers maintain a height of `52px`.
- **Card Gaps:** List collections of ride proposals use `space-md` (`12px`) separation over `space-lg` (`16px`) padding inside card borders.

## Elevation & Depth

Visual depth is communicated through clean surface staging, avoiding heavy Skeuomorphism while grounding floating interaction sheets.

- **Level 0 (Floor/Map View):** Canvas background `#F4F4F5` or active interactive map tiles.
- **Level 1 (Resting Cards):** `#FFFFFF` surfaces with subtle ambient shadow: `0 2px 8px rgba(0, 0, 0, 0.06)`, separated by soft 1px border lines using `#E4E4E7`.
- **Level 2 (Active/Floating Overlays):** Interactive quick-search bars, campus filters, and active ride cards: `0 4px 16px rgba(0, 0, 0, 0.08)`.
- **Level 3 (Draggable Bottom Sheets & Modals):** Grounded at the viewport floor with high-spread diffusion: `0 -6px 24px rgba(0, 0, 0, 0.12)`, topped with a drag handle (`#D4D4D8`, `36px × 4px`, `rounded-full`).

## Shapes

The geometric identity utilizes a consistent `roundedness: 2` (16px base on cards and primary modules), balanced by deliberate contrasting functional geometries.

- **Ride Waypoint Geometry:**
  - **Origin Point:** Circular node (`w-3 h-3`, 50% border radius) filled with `#16A34A` or `#111111`.
  - **Destination Point:** Square node (`w-3 h-3`, 0% border radius or 2px micro-curve) filled with `#FFCC00` or `#DC2626`.
  - **Connecting Track:** Continuous vertical 2px dash or solid line in `#D4D4D8`.
- **Surface Radii:** Cards, action sheets, and modal views leverage `16px` border-radii (`rounded-2xl`).
- **Interactive Controls:** Buttons, text inputs, and filter chips utilize uniform `12px` to `16px` corner curvature. Badges and micro-status indicators utilize full pill geometries (`9999px`).

## Components

### 1. Primary Action Buttons
- **Height & Bounds:** Height is locked at `52px` with a `12px` or `16px` corner radius.
- **Primary CTA:** Solid `#FFCC00` background, `#111111` typography (`label-lg`), bold weight. Active state drops brightness by 6%.
- **Secondary CTA:** Solid `#111111` background, `#FFFFFF` typography.
- **Ghost/Tertiary:** Transparent background, `1px` border in `#E4E4E7`, `#111111` text.

### 2. Route Timeline (Wayfinding Component)
- **Anatomy:** Vertical stacked layout with Origin (top) and Destination (bottom).
- Left gutter features the green circle (Origin) and dark square (Destination) joined by an unbroken 2px vertical rule (`#E4E4E7`).
- Right content block displays departure time, campus point (e.g., "Sede Centro"), destination address, and optional intermediate stops.

### 3. Ride Proposal Cards
- **Container:** Pure `#FFFFFF`, `16px` border-radius, `0 2px 8px rgba(0, 0, 0, 0.06)` shadow, `16px` internal padding.
- **Top Row:** Driver profile picture (`40px` circle with verified institutional checkmark), driver name, student course abbreviation badge, and UTFPR rating (`★ 4.9`).
- **Middle Row:** Full Waypoint Route timeline.
- **Bottom Row:** Available seats pill (e.g., "3 vagas"), departure countdown, and `R$` monetary amount highlighted using `display-currency` (`24px-26px` bold).

### 4. Draggable Bottom Sheet
- **Anatomy:** `#FFFFFF` background, `24px` radius applied to top-left and top-right corners only.
- Features a centered handle (`36px × 4px`, `#D4D4D8`) at `8px` top margin.
- Supports 3 snap positions: collapsed (quick summary), half-screen (ride selection/options), and expanded (full-height scrollable form with map dimmed).

### 5. Status & Information Badges (Pills)
- **Shape:** Fully rounded ends (`rounded-full`), padding `4px 10px`.
- **Confirmed / Confirmed:** Background `#DCFCE7`, text `#16A34A` (`label-pill`).
- **Pending / Waiting:** Background `#FEF3C7`, text `#D97706` (`label-pill`).
- **Cancelled:** Background `#FEE2E2`, text `#DC2626` (`label-pill`).
- **Campus Identifier:** Background `#F4F4F5`, text `#111111`, border `#E4E4E7`.

### 6. Input Fields & Search Triggers
- **Height:** `48px` or `52px` to guarantee accessible mobile touch ergonomics.
- **Styling:** Recessed `#F4F4F5` fill or crisp `#FFFFFF` container with `1px` `#E4E4E7` border. Focus state replaces border with a sharp `2px` `#111111` outline or `#FFCC00` halo.

### 7. Bottom Navigation Bar
- Fixed bottom sheet container with `56px` height plus device safe area margin.
- 4 tabs: "Início" (Carona/Mapa), "Buscar", "Oferecer", and "Perfil/Atividades".
- Active tab uses `#111111` fill icon with a small `#FFCC00` dot indicator below; inactive tabs use `#71717A`.