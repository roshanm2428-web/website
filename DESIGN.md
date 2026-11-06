---
name: Smart Library System
colors:
  surface: '#faf8ff'
  surface-dim: '#d2d9f4'
  surface-bright: '#faf8ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f3ff'
  surface-container: '#eaedff'
  surface-container-high: '#e2e7ff'
  surface-container-highest: '#dae2fd'
  on-surface: '#131b2e'
  on-surface-variant: '#434655'
  inverse-surface: '#283044'
  inverse-on-surface: '#eef0ff'
  outline: '#737686'
  outline-variant: '#c3c6d7'
  surface-tint: '#0053db'
  primary: '#004ac6'
  on-primary: '#ffffff'
  primary-container: '#2563eb'
  on-primary-container: '#eeefff'
  inverse-primary: '#b4c5ff'
  secondary: '#712ae2'
  on-secondary: '#ffffff'
  secondary-container: '#8a4cfc'
  on-secondary-container: '#fffbff'
  tertiary: '#006058'
  on-tertiary: '#ffffff'
  tertiary-container: '#007b71'
  on-tertiary-container: '#b3fff3'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dbe1ff'
  primary-fixed-dim: '#b4c5ff'
  on-primary-fixed: '#00174b'
  on-primary-fixed-variant: '#003ea8'
  secondary-fixed: '#eaddff'
  secondary-fixed-dim: '#d2bbff'
  on-secondary-fixed: '#25005a'
  on-secondary-fixed-variant: '#5a00c6'
  tertiary-fixed: '#89f5e7'
  tertiary-fixed-dim: '#6bd8cb'
  on-tertiary-fixed: '#00201d'
  on-tertiary-fixed-variant: '#005049'
  background: '#faf8ff'
  on-background: '#131b2e'
  surface-variant: '#dae2fd'
typography:
  display-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
  display-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  title-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 24px
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
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
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '700'
    lineHeight: 14px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 2rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system is engineered for modern smart library environments, academic resource centers, and digital media archives. It marries institutional authority with high-velocity digital utility. 

The aesthetic is Modern Corporate with refined editorial clarity: crisp white surfaces, calibrated jewel-toned accents, and structured visual divisions. The interface projects efficiency, order, and intellectual prestige without feeling bureaucratic. Interaction patterns prioritize density, rapid catalog scanning, and zero ambiguity regarding physical availability and transaction deadlines.

## Colors

The palette leverages an authoritative Royal Blue (`#2563EB`) as the primary interactive driver and a vibrant Amethyst Purple (`#7C3AED`) as the secondary accent for advanced categorization, digital services, and discovery actions. Deep Slate (`#0F172A`) establishes grounding neutral typography and crisp structural lines.

### Functional Status & High-Contrast Badges
Status indicators demand instant legibility against crisp white surfaces:
- **Available / On Shelf:** Vibrant Emerald (`#059669`) background with crisp white text, or pale tint (`#ECFDF5`) with deep emerald text (`#065F46`).
- **Circulated / Checked Out:** Deep Amber (`#D97706`) background with white text, or pale amber (`#FFFBEB`) with dark amber text (`#92400E`).
- **Overdue / Outstanding Fine / Reserved Lockout:** High-contrast Crimson (`#DC2626`) background with pure white text (`#FFFFFF`) to ensure critical urgency.
- **Digital / Electronic Asset:** Vibrant Purple (`#7C3AED`) background with pure white text (`#FFFFFF`).

Surfaces strictly prioritize pure crisp white (`#FFFFFF`) for elevated cards, framed by subtle neutral borders (`#E2E8F0`) over a calm canvas wash (`#F8FAFC`).

## Typography

The typographic system utilizes **Plus Jakarta Sans** for headlines and display tiers, providing geometric precision, modern warmth, and clear structural hierarchy. **Inter** handles all body copy, tabular catalog data, metadata rows, and status badges to guarantee supreme legibility across small print identifiers (ISBNs, call numbers, barcode labels, and patron IDs).

### Hierarchy Implementation
- **Catalog Titles:** `title-md` and `headline-sm` with `Plus Jakarta Sans` semi-bold weights ensure book titles stand out clearly from accompanying author, publisher, and edition metadata.
- **Classification & Call Numbers:** Standardized on `label-sm` or `label-md` with `Inter` uppercase styling and tight letter tracking for rapid spine reading.
- **Dense Data & Ledgers:** Circulation transactions, due dates, and fine balances leverage `body-md` and tabular numeric adjustments for horizontal scanning.

## Layout & Spacing

The layout model is built on an adaptive fluid grid with a desktop maximum content envelope of 1440px. 

### Grid Architecture
- **Desktop (1024px+):** 12-column layout with 24px (`1.5rem`) gutters and 32px (`2rem`) outer margins. Supports persistent left-hand navigation rail (240px) and a primary content canvas that easily divides into 2-column or 3-column catalog grids.
- **Tablet (768px – 1023px):** 8-column layout with 16px (`1rem`) gutters and 24px (`1.5rem`) margins. Navigation collapses into an icon bar or drawer.
- **Mobile (< 768px):** 4-column layout with 16px (`1rem`) gutters and 16px (`1rem`) screen margins. Catalog items transition to stacked linear row cards to maximize thumbnail and metadata clarity.

## Elevation & Depth

This system avoids heavy drop shadows, instead pairing crisp border containment with subtle, low-opacity ambient shadows tinted slightly with slate blue (`rgb(15 23 42 / 0.06)`).

### Elevation Hierarchy
- **Level 0 (Canvas):** `#F8FAFC` background. Completely flat.
- **Level 1 (Default Cards & Surfaces):** Pure white (`#FFFFFF`) with a 1px border of `#E2E8F0` and an ambient shadow of `0 1px 3px 0 rgba(15, 23, 42, 0.05)`. Used for catalog cards, search toolbars, and patron history rows.
- **Level 2 (Hover & Active States):** 1px border shifted to `#CBD5E1` with an elevated shadow of `0 4px 12px -2px rgba(15, 23, 42, 0.08)`. Indicates clickable books, loans, or interactive rows.
- **Level 3 (Modals, Slide-over Shelves & Drawers):** `#FFFFFF` with `0 20px 25px -5px rgba(15, 23, 42, 0.12), 0 8px 10px -6px rgba(15, 23, 42, 0.04)`. Accompanied by a 30% slate backdrop overlay blur (`backdrop-blur-sm`).

## Shapes

The system implements a controlled `roundedness: 2` (base radius of `0.5rem` / 8px). This creates a structured yet welcoming interface that reflects modern cataloging architecture.

- **Inputs, Buttons, Dropdowns:** `rounded` (8px / `0.5rem`).
- **Cards, Panels, Modal dialogs:** `rounded-lg` (16px / `1rem`).
- **Status Badges, Availability Chips:** `rounded-full` (pill shape) to differentiate meta tags from structural cards and interactive buttons.
- **Book Cover Media:** `rounded` (6px to 8px) with a subtle inset border (`inset 0 0 0 1px rgba(0,0,0,0.06)`) simulating real book binding.

## Components

### Buttons
- **Primary:** Solid `#2563EB` with `#FFFFFF` text, subtle transition to hover state (`#1D4ED8`). Padding: 10px 18px.
- **Secondary / Action:** Solid `#7C3AED` with `#FFFFFF` text, hover state (`#6D28D9`). Used for resource checkout, holds, and digital downloads.
- **Outline / Ghost:** 1px border `#E2E8F0`, transparent background, `#0F172A` text. Hover fills `#F1F5F9`. Used for secondary filtering and catalog exports.

### High-Contrast Status Badges
Badges communicate immediate operational status through a high-contrast pill format:
- **Available:** Background `#ECFDF5`, text `#065F46`, border 1px solid `#A7F3D0`. Includes a solid emerald dot prefix.
- **Checked Out / In Circulation:** Background `#FFFBEB`, text `#92400E`, border 1px solid `#FDE68A`.
- **Overdue / Fine Active:** Solid Crimson (`#DC2626`) background with bold white (`#FFFFFF`) text for critical visibility.
- **Reference Only:** Background `#F1F5F9`, text `#475569`, border 1px solid `#CBD5E1`.

### Catalog & Book Cards
- Structured white surface, `rounded-lg`, 1px border (`#E2E8F0`).
- Top/Left: Fixed-ratio book cover slot (2:3 aspect ratio) with subtle inner edge shadow.
- Center/Right: Title (`title-md`), author metadata (`body-sm`), classification tag/call number (`label-sm`).
- Bottom row: High-contrast availability badge paired with primary quick-reserve CTA.

### Input Fields & Search Bars
- Universal search input with prominent prefix search icon, shortcut tag (`⌘K`), white background, 1px border (`#CBD5E1`).
- Focus ring: 2px solid `#2563EB` with 2px offset.
- Compact metadata filters (genre, branch location, publication year) styled as discrete dropdown buttons with trailing disclosure arrows.

### Data Tables & Circulation Lists
- Alternate row striping avoided in favor of clean 1px bottom border separators (`#F1F5F9`).
- Hover state transitions row background to `#F8FAFC`.
- Call numbers styled in monospaced/neutral high-readability labels.
- Fines column highlighted with red text token when active balance exceeds $0.00.