---
version: alpha
name: Ketto-design-system
description: A story-led crowdfunding and giving platform built on a clean near-white canvas, with Ketto Teal (#288B91) as the brand accent. Teal is used as a few accents per screen (the main CTA, links, active tabs, progress bars and icons), never as a flood. Type pairs Proxima Nova for everything functional with Source Serif Pro Bold Italic reserved for emotional, stylistic Display moments. Every interactive element is pill-shaped, cards round by size (16px or 24px), and surfaces stay mostly flat. App screens stay primarily white, and primary buttons are always teal. Product accents (purple for Animal SIP, blue for new launches) are a guideline for promotional and marketing surfaces, not app UI.

colors:
  # Brand
  primary: "#288B91"
  primary-hover: "#1D6266"
  primary-pressed: "#174A4D"       # Figma name: ketto/tertiary
  primary-light: "#DDF6F7"         # Figma name: ketto/disabled → renamed ketto/light
  on-primary: "#FCFCFC"
  # Neutrals
  white: "#FCFCFC"
  black-1: "#F3F3F3"
  black-2: "#CCCCCC"
  black-3: "#A6A6A6"
  black-4: "#737373"
  black-5: "#404040"
  black-6: "#262626"
  # Product accents
  blue-1: "#DEEFFF"
  blue-2: "#B0D9FF"
  blue-3: "#55AAFB"
  blue-4: "#2185E4"
  green-1: "#D8FBEC"
  green-2: "#ABEFCF"
  green-3: "#5BBE90"
  green-4: "#16A160"
  orange-1: "#FFE6D8"
  orange-2: "#FFCFB2"
  orange-3: "#FF9659"
  orange-4: "#FF7B2E"
  purple-1: "#E4DEFF"
  purple-2: "#C3BAF1"
  purple-3: "#8D91E2"
  purple-4: "#5C62D5"
  # State
  success: "#5BBE90"
  intermediate: "#FFBE00"
  error: "#EF5461"
  # Supporting
  error-light: "#FDE7E9"
  scrim: "#000000"

typography:
  display-lg:
    fontFamily: "'Source Serif Pro', 'Source Serif 4', Georgia, serif"
    fontSize: 36px
    fontWeight: 700
    fontStyle: italic
    lineHeight: 1.2
  display-md:
    fontFamily: "'Source Serif Pro', 'Source Serif 4', Georgia, serif"
    fontSize: 28px
    fontWeight: 700
    fontStyle: italic
    lineHeight: 1.2
  display-sm:
    fontFamily: "'Source Serif Pro', 'Source Serif 4', Georgia, serif"
    fontSize: 24px
    fontWeight: 700
    fontStyle: italic
    lineHeight: 1.2
  h1:
    fontFamily: "'Proxima Nova', Figtree, Montserrat, -apple-system, system-ui, sans-serif"
    fontSize: 36px
    fontWeight: 800
    lineHeight: 1.2
  h2:
    fontFamily: "'Proxima Nova', Figtree, Montserrat, sans-serif"
    fontSize: 36px
    fontWeight: 600
    lineHeight: 1.2
  h3:
    fontFamily: "'Proxima Nova', Figtree, Montserrat, sans-serif"
    fontSize: 28px
    fontWeight: 600
    lineHeight: 1.2
  h4:
    fontFamily: "'Proxima Nova', Figtree, Montserrat, sans-serif"
    fontSize: 24px
    fontWeight: 600
    lineHeight: 1.2
  h5:
    fontFamily: "'Proxima Nova', Figtree, Montserrat, sans-serif"
    fontSize: 20px
    fontWeight: 600
    lineHeight: 1.2
  h6:
    fontFamily: "'Proxima Nova', Figtree, Montserrat, sans-serif"
    fontSize: 17px
    fontWeight: 600
    lineHeight: 1.2
  body-lg:
    fontFamily: "'Proxima Nova', Figtree, Montserrat, sans-serif"
    fontSize: 17px
    fontWeight: 400
    lineHeight: 1.5
  body-base:
    fontFamily: "'Proxima Nova', Figtree, Montserrat, sans-serif"
    fontSize: 14px
    fontWeight: 400
    lineHeight: 1.5
  body-base-bold-italic:
    fontFamily: "'Proxima Nova', Figtree, Montserrat, sans-serif"
    fontSize: 14px
    fontWeight: 700
    fontStyle: italic
    lineHeight: 1.5
  body-sm:
    fontFamily: "'Proxima Nova', Figtree, Montserrat, sans-serif"
    fontSize: 12px
    fontWeight: 400
    lineHeight: 1.5
  subtitle-lg:
    fontFamily: "'Proxima Nova', Figtree, Montserrat, sans-serif"
    fontSize: 17px
    fontWeight: 700
    lineHeight: 1.3
  subtitle-base:
    fontFamily: "'Proxima Nova', Figtree, Montserrat, sans-serif"
    fontSize: 14px
    fontWeight: 700
    lineHeight: 1.3
  subtitle-sm:
    fontFamily: "'Proxima Nova', Figtree, Montserrat, sans-serif"
    fontSize: 12px
    fontWeight: 700
    lineHeight: 1.3
  tag-xsmall:
    fontFamily: "'Proxima Nova', Figtree, Montserrat, sans-serif"
    fontSize: 10px
    fontWeight: 400
    lineHeight: 1.3
  tag-xsmall-bold:
    fontFamily: "'Proxima Nova', Figtree, Montserrat, sans-serif"
    fontSize: 10px
    fontWeight: 700
    lineHeight: 1.3
  label:
    fontFamily: "'Proxima Nova', Figtree, Montserrat, sans-serif"
    fontSize: 12px
    fontWeight: 700
    lineHeight: 1.3
    letterSpacing: 0.1em
    textTransform: uppercase
    # Use for UPPERCASE tags, labels, and small button labels

rounded:
  xs: 2px   # checkboxes only
  sm: 8px   # snackbars, plain tooltips
  base: 16px   # elements 110–314px
  lg: 24px   # elements ≥315px, and <110px minimum
  full: 9999px   # buttons, chips, avatars, icon buttons

spacing:
  xxs: 4px
  xs: 8px
  sm: 12px
  base: 16px
  md: 24px
  lg: 32px
  xl: 40px
  xxl: 48px
  section: 64px

grid:
  mobile-android: { width: 360dp, columns: 12, margin: 16px, gutter: 8px, gutter-loose: 16px }
  mobile-ios:     { width: 375pt, columns: 12, margin: 16px, gutter: 8px, gutter-loose: 16px }
  desktop:        { breakpoint: 768px, max-width: 1440px, columns: 12, gutter: 24px, margin: TBD }
  module:         { padding-y: 24px, gap: 16px, gap-loose: 24px, between-modules: 0px }

elevation:
  flat: none
  float: "0 2px 8px rgba(0,0,0,0.08)"   # the single shadow tier

components:
  button-primary-lg:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.on-primary}"
    typography: "{typography.subtitle-lg}"
    rounded: "{rounded.full}"
    padding: 8px 16px
    height: 60px
    minWidth: 315px
  button-primary-md:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.on-primary}"
    typography: "{typography.subtitle-base}"
    rounded: "{rounded.full}"
    padding: 8px 16px
    height: 48px
    minWidth: 113px
  button-primary-sm:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.on-primary}"
    typography: "{typography.label}"
    rounded: "{rounded.full}"
    padding: 8px 16px
    height: 32px
    minWidth: 84px
  button-primary-hover:
    backgroundColor: "{colors.primary-hover}"
  button-primary-pressed:
    backgroundColor: "{colors.primary-pressed}"
  button-primary-white:
    backgroundColor: "{colors.white}"
    textColor: "{colors.primary}"
    rounded: "{rounded.full}"
  button-tonal:
    backgroundColor: "{colors.primary-light}"
    textColor: "{colors.primary}"
    rounded: "{rounded.full}"
  button-ghost:
    backgroundColor: transparent
    borderColor: "{colors.black-2}"
    textColor: "{colors.primary}"
    rounded: "{rounded.full}"
  button-text:
    backgroundColor: transparent
    textColor: "{colors.primary}"
  button-danger:
    backgroundColor: "{colors.error}"
    textColor: "{colors.on-primary}"
    rounded: "{rounded.full}"
  button-danger-tonal:
    backgroundColor: "{colors.error-light}"
    textColor: "{colors.error}"
    rounded: "{rounded.full}"
  icon-button:
    rounded: "{rounded.full}"
    sizes: [60px, 48px, 32px]
    iconSizes: [24px, 20px, 16px]   # per button size
  chip:
    backgroundColor: transparent
    borderColor: "{colors.black-2}"
    textColor: "{colors.black-4}"
    typography: "{typography.subtitle-sm}"
    rounded: "{rounded.full}"
    height: 32px
    padding: 0 12px
  chip-selected:
    backgroundColor: "{colors.primary-light}"
    textColor: "{colors.primary-pressed}"
  card:
    backgroundColor: "{colors.white}"
    borderColor: "{colors.black-2}"
    rounded: "{rounded.base}"   # {rounded.lg} when ≥315px wide
    padding: 16px
  text-input:
    backgroundColor: "{colors.white}"
    borderColor: "{colors.black-3}"
    textColor: "{colors.black-5}"
    typography: "{typography.body-lg}"
    rounded: "{rounded.base}"
    height: 56px
    padding: 0 16px
  text-input-focus:
    borderColor: "{colors.primary}"
    borderWidth: 2px
  text-input-error:
    borderColor: "{colors.error}"
    borderWidth: 2px
  progress-linear:
    trackColor: "{colors.primary-light}"
    indicatorColor: "{colors.primary}"
    rounded: "{rounded.full}"
    height: 4px
  dialog:
    backgroundColor: "{colors.white}"
    rounded: "{rounded.lg}"
    padding: 24px
  bottom-sheet:
    backgroundColor: "{colors.white}"
    rounded: "{rounded.lg} {rounded.lg} 0 0"
  snackbar:
    backgroundColor: "{colors.black-6}"
    textColor: "{colors.white}"
    typography: "{typography.body-base}"
    rounded: "{rounded.sm}"
  nav-bar:
    backgroundColor: "{colors.white}"
    activeIndicator: "{colors.primary-light}"
    typography: "{typography.tag-xsmall-bold}"
    height: 80px
  campaign-card:
    backgroundColor: "{colors.white}"
    rounded: "{rounded.base}"     # 265px wide → 16px per Roundness rule
    shadow: "{elevation.float}"
    width: 265px
    height: 342px
  campaign-card-image:
    width: 265px
    height: 165px               # ≈ 8:5
  campaign-card-body:
    padding: 16px
    gap: 16px
  campaign-card-urgency-tag:
    backgroundColor: "{colors.white}"
    textColor: "{colors.error}"
    typography: "{typography.label}"
    rounded: "0 {rounded.lg} 0 {rounded.lg}"
  campaign-card-title:
    textColor: "{colors.black-6}"
    typography: "{typography.h5}"
    maxLines: 2
  campaign-card-progress:
    trackColor: "{colors.black-1}"
    indicatorColor: "{colors.primary}"
    rounded: "{rounded.full}"
    height: 6px
  campaign-card-amount:
    textColor: "{colors.black-5}"
    typography: "{typography.body-base}"   # amount figure in bold
  campaign-card-supporters-icon:
    backgroundColor: "{colors.blue-3}"
    iconColor: "{colors.white}"
    rounded: "{rounded.full}"
    size: 16px
  campaign-card-donate:
    component: "{components.button-primary-sm}"
    typography: "{typography.label}"
    height: 32px
    minWidth: 84px              # width grows with the label
  cause-card:
    backgroundColor: "{colors.white}"
    rounded: "{rounded.lg}"
    shadow: "{elevation.float}"
    width: 255px               # Large card width
    height: 310px              # Fixed height
    padding: 16px              # All sides
  cause-card-image:
    width: 265px               # Fixed, edge to edge
    height: 165px              # 8:5 aspect ratio
  cause-card-new-badge:
    backgroundColor: "{colors.blue-3}"
    textColor: "{colors.white}"
    typography: "{typography.subtitle-sm}"
    rounded: "{rounded.full}"
    width: 48px
    height: 18px
  cause-card-title:
    textColor: "{colors.black-6}"
    typography: "{typography.h4}"
  cause-card-description:
    textColor: "{colors.black-4}"
    typography: "{typography.body-lg}"
  cause-card-donors:
    textColor: "{colors.black-6}"
    typography: "{typography.subtitle-lg}"
  cause-card-cta:
    component: "{components.button-primary-md}"
    typography: "{typography.label}"
  amount-picker:
    container: "{components.bottom-sheet}"
    padding: 24px 16px 0
  amount-picker-title:
    textColor: "{colors.black-6}"
    typography: "{typography.h5}"
  amount-picker-description:
    textColor: "{colors.black-4}"
    typography: "{typography.body-base}"
    marginTop: 8px
  amount-tile:
    backgroundColor: "{colors.white}"
    borderColor: "{colors.black-2}"
    borderWidth: 1px
    textColor: "{colors.black-6}"
    rounded: "{rounded.base}"    # 109px → 16px (Roundness rule)
    size: 109px   # 1:1:1 element width
    gap: 8px
  amount-tile-amount:
    typography: "{typography.h5}"   # bold weight
  amount-tile-period:
    textColor: "{colors.black-4}"
    typography: "{typography.body-base}"
  amount-tile-selected:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.white}"
    periodOpacity: 0.8
  amount-tile-popular-banner:
    backgroundColor: "{colors.primary}"
    selectedBackground: "{colors.primary} @ 80% over white"
    textColor: "{colors.white}"
    typography: "{typography.label}"
    height: 24px
  amount-picker-custom:
    component: "{components.button-text}"
    typography: "{typography.subtitle-base}"
    textDecoration: underline
    height: 48px
  amount-picker-footer:
    borderTop: "1px {colors.black-1}"
    padding: 16px
  amount-picker-cta:
    component: "{components.button-primary-lg}"
    width: 343px
    disabledLabel: "Select an amount"
---

# Ketto Design System

> Anything not yet decided is listed under [Known Gaps](#known-gaps).

## Overview

Ketto is a crowdfunding and giving platform. The experience is a **balanced mix**: **story first**, with photos and beneficiary narratives drawing people in; **trust close behind**, with verified badges, raised amounts and progress bars; and **urgency only on campaign pages**, where the donate CTA and deadlines matter.

The canvas is a near-white **`{colors.white}`** (#FCFCFC) with dark-grey ink (`{colors.black-5}` #404040) for text, never pure black. **Ketto Teal** (`{colors.primary}` #288B91) is the brand accent. It appears as **a few accents per screen**: the main CTA, links, active tabs, progress bars and key icons.

Type is **Proxima Nova** for everything functional. **Source Serif Pro Bold Italic** is reserved for Display headings, the one emotional, editorial voice in the system.

The shape language is **soft and pill-shaped**. Every button, chip and icon button is fully rounded. Cards and surfaces round by their size (16px or 24px), and there are no hard corners on interactive elements.

**Key Characteristics**
- One brand accent, used as a few moments per screen rather than as a flood of colour.
- **Primary buttons are always teal**, on every product and every screen.
- App screens are primarily white. Product accent colours are for promotional and marketing surfaces.
- A serif Display face for emotional headlines; a clean sans for everything else.
- Pill-shaped everything; card radius depends on size.
- Mostly flat surfaces, with one soft shadow tier for floating elements.
- Modular layout: modules stack with 0px between them, and each module carries its own 24px padding.
- An 8pt spacing system with 4px and 12px half-steps.

---

## Colors

### Brand
- **Ketto Teal** (`{colors.primary}` #288B91): primary CTAs, links, active tabs, progress bars, selected states and key icons. Use as a few accents per screen, not as large backgrounds.
- **Teal Hover** (`{colors.primary-hover}` #1D6266): the hover state of filled teal elements, and small teal text on white (it passes contrast).
- **Teal Pressed** (`{colors.primary-pressed}` #174A4D): the pressed state, and text on `primary-light` surfaces. _Figma name: `ketto/tertiary`._
- **Teal Light** (`{colors.primary-light}` #DDF6F7): tonal button fills, selected chips, progress tracks, the active nav indicator, and soft brand surfaces. _Renamed from `ketto/disabled` to `ketto/light`._

### Product Accents
Each accent has four levels. Levels 1–3 are for backgrounds, and level 4 is for titles and body text.

| Palette | Product | Usage |
|---|---|---|
| **Teal** (brand) | Crowdfunding | Default for all core fundraising surfaces |
| **Purple** | Animal SIP | Promotional cards, banners and social media |
| **Blue** | New launches (Ketto One, HealthFirst, etc.) | Promotional surfaces; in-app, only small touches such as the "new" badge |
| **Green** | — | Minimal: illustrations and soft card backgrounds only |
| **Orange** | — | Minimal: illustrations and soft card backgrounds only |

> **Guideline, not a hard rule.** Product accents are for **promotional cards, banners, campaigns and social media**. App screens stay **primarily white**, and **primary buttons are always `primary` teal**, whatever the product. Inside the app, accents appear only as small touches, such as the blue "new" badge.

Don't mix product accents on one surface. Green and orange never carry meaning.

| Level | Blue | Green | Orange | Purple |
|---|---|---|---|---|
| 1 | #DEEFFF | #D8FBEC | #FFE6D8 | #E4DEFF |
| 2 | #B0D9FF | #ABEFCF | #FFCFB2 | #C3BAF1 |
| 3 | #55AAFB | #5BBE90 | #FF9659 | #8D91E2 |
| 4 | #2185E4 | #16A160 | #FF7B2E | #5C62D5 |

### Neutrals

| Token | Hex | Usage |
|---|---|---|
| `white` | #FCFCFC | Page canvas, card surfaces, text on dark or teal backgrounds |
| `black-1` | #F3F3F3 | App background, dividers, filled-card surface |
| `black-2` | #CCCCCC | Borders, outlines, disabled fills |
| `black-3` | #A6A6A6 | Input borders, placeholder text, labels |
| `black-4` | #737373 | Secondary text, supporting copy |
| `black-5` | #404040 | Primary text, headings |
| `black-6` | #262626 | Big headers, snackbar and tooltip surfaces |

### State

| Token | Hex | Usage |
|---|---|---|
| `success` | #5BBE90 | Active, success, verified (same value as `green-3`) |
| `intermediate` | #FFBE00 | In progress, in review |
| `error` | #EF5461 | Errors, paused, destructive actions |
| `error-light` | #FDE7E9 | Tonal danger button fill, error banners |

### Scrim
- **Scrim** (`{colors.scrim}`): black at 32% opacity, behind dialogs and modal bottom sheets.

---

## Typography

### Font Families
- **Proxima Nova**: headings, body, subtitles, tags, labels and buttons. _Fallbacks: Figtree, Montserrat, then the system sans._
- **Source Serif Pro**: Display styles only, always Bold Italic. _Fallback: Source Serif 4 (free, the same family), then Georgia._

The root font size is **14px**, so `1rem = 14px`.

### Hierarchy

| Token | Size (rem) | Weight | Line height | Tracking | Use |
|---|---|---|---|---|---|
| `display-lg` | 36px (2.571) | 700 Italic · Serif | 120% | 0 | Hero emotional headlines on campaign and landing pages |
| `display-md` | 28px (2.000) | 700 Italic · Serif | 120% | 0 | Section-level stylistic headings |
| `display-sm` | 24px (1.714) | 700 Italic · Serif | 120% | 0 | Pull quotes, impact statements |
| `h1` | 36px (2.571) | 800 ExtraBold | 120% | 0 | Page titles |
| `h2` | 36px (2.571) | 600 Semibold | 120% | 0 | Major section titles |
| `h3` | 28px (2.000) | 600 Semibold | 120% | 0 | Section titles |
| `h4` | 24px (1.714) | 600 Semibold | 120% | 0 | Sub-section titles |
| `h5` | 20px (1.429) | 600 Semibold | 120% | 0 | Card titles, dialog titles |
| `h6` | 17px (1.214) | 600 Semibold | 120% | 0 | Small titles, app bar titles |
| `body-lg` | 17px (1.214) | 400 Regular | 150% | 0 | Campaign story text, input values |
| `body-base` | 14px (1.000) | 400 Regular | 150% | 0 | Default running text |
| `body-base-bold-italic` | 14px (1.000) | 700 Italic | 150% | 0 | Emphasised quotes within body |
| `body-sm` | 12px (0.857) | 400 Regular | 150% | 0 | Meta, helper text, captions |
| `subtitle-lg` | 17px (1.214) | 700 Bold | 130% | 0 | Large button labels, emphasised values |
| `subtitle-base` | 14px (1.000) | 700 Bold | 130% | 0 | Medium button labels, tab labels, amounts |
| `subtitle-sm` | 12px (0.857) | 700 Bold | 130% | 0 | Chip labels, small emphasis |
| `tag-xsmall` | 10px (0.714) | 400 Regular | 130% | 0 | Tiny meta |
| `tag-xsmall-bold` | 10px (0.714) | 700 Bold | 130% | 0 | Nav bar labels, badges |
| `label` | 12px (0.857) | 700 Bold | 130% | 10% | UPPERCASE tags, labels, and small button labels |

### Principles
- **Titles use Headings. Body copy and subtitles use Body and Subtitle. Tags use Tags and Labels.**
- **Display is limited.** Use it only for stylistic headings that create visual impact, and at most once per screen. It's the brand's emotional voice, so don't use it for functional UI.
- Headings are Semibold; only `h1` goes ExtraBold, as the single heaviest moment on a page.
- Text is never pure black: use `black-5` for primary text and `black-4` for secondary text.

---

## Layout

### Spacing System
- **Base unit:** 8px, with **4px and 12px half-steps**.
- **Tokens:** `xxs` 4 · `xs` 8 · `sm` 12 · `base` 16 · `md` 24 · `lg` 32 · `xl` 40 · `xxl` 48 · `section` 64.

### Grids
Grids are **guidelines, not strict rules**.

| Platform | Width | Columns | Margin | Gutter (Default / Loose) |
|---|---|---|---|---|
| Android | 360dp | 12 | 16 | 8 / 16 |
| iOS / mobile web | 375pt | 12 | 16 | 8 / 16 |
| Desktop web (≥768px) | max 1440px | 12 | _TBD_ | 24 |

The standard design frame is **375 × 812px**.

### Modules
Ketto is **modular**. Modules stack with **0px** between them. Inside a module:

| Type | Top/bottom padding | Gap between elements |
|---|---|---|
| Default | 24px | 16px |
| Loose | 24px | 24px |

### Element Widths (375px, Default grid)
Content width is 375 − 2 × 16 = **343px**.

| Layout | Width |
|---|---|
| Full width | 343px |
| Large card | 255px |
| Two across (1:1) | 168px |
| Medium card | 168px |
| Three across (1:1:1) | 109px |
| Small card | 109px |
| Carousel 2:1 | 226px |
| Carousel 7:5 | 197px |
| Campaign Card | 265px |

**Card width standards:**
- **Full:** 343px (edge-to-edge, minus gutters)
- **Large:** 255px (Cause Card, multi-section cards)
- **Medium:** 168px (smaller grouped cards)
- **Small:** 109px (compact cards, 3 across)

Carousel cards are narrower than the screen so the next card peeks in, which shows the row scrolls.

### Roundness
Pick the radius from the element's size.

| Element size | Radius |
|---|---|
| ≥ 315px | `lg` 24px |
| 110–314px | `base` 16px |
| < 110px | 24px or more, usually `full` |

Exceptions: text fields use 16px at any width; checkboxes use 2px; snackbars and plain tooltips use 8px.

---

## Elevation

Ketto is **mostly flat**. There are two tiers:

- **Flat:** pages, modules, cards at rest, inputs and lists. This covers almost every surface. Use a `black-2` border or a `black-1` fill to separate surfaces, not a shadow.
- **Float** (`0 2px 8px rgba(0,0,0,0.08)`): anything that floats above content, such as sticky donate bars, bottom sheets, menus, snackbars and hovered cards. _The exact value is derived._
- **Scrim:** black at 32% behind modals.

---

## Components

### Buttons

All buttons are **pill-shaped** (`full`). Hierarchy follows Material Design 3.

| Level | Style | Look | Use |
|---|---|---|---|
| Primary | **Fill – Default** | `primary` fill, white label | The single most important action on a light background |
| | **Fill – White** | `white` fill, `primary` label | The same action on dark or coloured backgrounds |
| Secondary | **Tonal** | `primary-light` fill, `primary` label | Beside a primary, e.g. *Login* next to *Sign up* |
| Tertiary | **Ghost** | `black-2` outline, `primary` label | A lower-emphasis alternative |
| | **Text** | Label only | The least emphasis: *Skip*, *Learn more* |

**Variants**
- **Default:** teal.
- **Danger:** `error`. Primary danger is a solid red fill with a white label; tonal danger uses `error-light`.
- **Disabled:** a faded version of the style.

**Sizes** (heights are fixed; widths are minimums that grow with the label)

| Size | W × H | Use when the available width is | Label | Icon |
|---|---|---|---|---|
| Large | 315 × 60 | 255–343px | `subtitle-lg` | 20px |
| Medium | 113 × 48 | 168–255px | `subtitle-base` | 16px |
| Small | 84 × 32 | < 168px | `label` (UPPERCASE) | 12px |

- **Padding:** 16px horizontal, 8px vertical.
- **Icon positions:** trailing (`Sign up →`), leading (`🔍 Sign up`) or none.

**States** (MD3 state layers)

| Style | Hover | Pressed | Disabled |
|---|---|---|---|
| Fill – Default | `primary-hover` | `primary-pressed` | 38% opacity |
| Danger fill | error + 8% black | error + 12% black | 38% opacity |
| Fill – White / Tonal / Ghost / Text | + 8% teal layer | + 10% teal layer | 38% opacity |

- **Keyboard focus:** a 2px `primary` ring, offset by 2px.

**Do / Don't**
- ✅ Pair Primary with Tonal, Ghost or Text.
- ❌ Don't place two primaries (Fill – Default and Fill – White) side by side.
- ✅ Use Fill – Default on light backgrounds and Fill – White on dark or coloured ones.
- ❌ Don't use Fill – White on light backgrounds, or Fill – Default on dark or coloured ones.
- ✅ For danger, prefer Tonal, Ghost or Text. Use a Primary danger button only in extreme cases.

### Campaign Card (`fundraiser`)

The core crowdfunding card. It's photo-first: the beneficiary's image leads, and trust signals (progress, amount, supporters) and a single donate CTA follow. This is the one card that carries **urgency**.

**Anatomy (top to bottom)**

| # | Part | Spec |
|---|---|---|
| 1 | **Container** | **265 × 342px**. `white` surface, float shadow. Radius `base` 16px, following the Roundness rule for 110–314px elements. |
| 2 | **Cover image** | **265 × 165px** (about 8:5), edge to edge and clipped to the card's top corners. Shows the beneficiary, never a stock image. |
| 3 | **Urgency tag** (optional) | Pinned top-right over the image. `white` background with a rounded bottom-left corner, clock icon + the word **URGENT** in `label`, `error`. No countdown. **Appears 14 days before the campaign end date.** Size hugs the label (no fixed width). |
| 4 | **Title** | `h5` (20px, 120%) in `black-6`. Max 2 lines (48px), then truncate with "…". |
| 5 | **Progress bar** | **6px** tall, full width (233px); `primary` indicator on a `black-1` track, `full` radius. |
| 6 | **Amount** | 4px below the bar, one line. `body-base` (14px, 150%) in `black-5`: **₹56,902** in bold + "left to be raised" in regular. |
| 7 | **Footer row** | 32px tall. Left: a **16px** `blue-3` circular icon with a `white` (#FCFCFC) glyph, a 4px gap, then **50k** (bold) + "supporters" (regular). Right: **DONATE** as a **Small** button (84 × 32px; the width grows with the label), Fill – Default, UPPERCASE. |

**Spacing:** 16px padding on all sides of the text area (content width 233px), and 16px between the title, the progress group and the footer.

**Rules**
- **One CTA:** the Donate button is the only action. The whole card also taps through to the campaign page.
- **The amount shows what's left to raise**, not the total raised, which puts the focus on the need.
- Large numbers follow the [Indian number format](#number--currency-format) rule.

### Cause Card (`cause cards`)

The homepage entry point for **monthly SIP** (recurring giving) causes. Unlike the Campaign Card, it sells an ongoing cause rather than one person's deadline, so it has **no urgency and no progress bar**. Cards stack vertically in a full-width list.

**Anatomy (top to bottom)**

| # | Part | Spec |
|---|---|---|
| 1 | **Container** | **255 × 310px**. `white` surface, `lg` 24px radius, float shadow. Padding 16px all sides. |
| 2 | **Cover image** | **265 × 165px** (8:5 aspect ratio, fixed), edge to edge and clipped to the card's top corners. Shows the cause, never a stock image. |
| 3 | **"new" badge** (optional) | Top-right over the image. **48 × 18px**. `blue-3` pill, white ★ icon + lowercase **new** in `subtitle-sm`, white. Blue marks a new launch. |
| 4 | **Title** | `h4` in `black-6`, one line (e.g. *Save a Child*), truncate with "…". |
| 5 | **Description** | `body-lg` in `black-4`, max 2 lines |
| 6 | **Footer row** | Left: donor count in bold `black-6` in Indian format (e.g. **22L Donors**, **1.5L Donors**). Right: **SIGN UP** button (Fill – Default, `label`). |

**Campaign Card vs Cause Card**

| | Campaign Card | Cause Card |
|---|---|---|
| Purpose | One-time donation to a person | Monthly SIP subscription to a cause |
| CTA | DONATE | SIGN UP |
| Urgency tag | Yes (red, top-right) | No; "new" badge instead (blue) |
| Progress bar | Yes | No |
| Social proof | Supporters + icon | Donors, text only |

### Amount Picker (Monthly SIP)

A bottom sheet where the donor picks a **monthly** donation amount before paying. All text uses **Proxima Nova**, following the system type scale.

**Anatomy (top to bottom)**

| # | Part | Spec |
|---|---|---|
| 1 | **Container** | Bottom sheet: `white` surface, 24px top corners, drag handle above the sheet. Padding 24px top and 16px sides (content width 343px). |
| 2 | **Title** | "Select donation amount" in `h5`, `black-6` |
| 3 | **Description** | `body-base` in `black-4`, 8px below the title; key words in bold (e.g. **every month**) |
| 4 | **Amount tiles** | 24px below the description. 3 square tiles, **109 × 109px** with **8px** gaps (the 1:1:1 element width). 1px `black-2` border, **16px** radius (the Roundness rule for 110–314px). Amount in `h5` bold (`black-6`), with "per month" in `body-base` (`black-4`) below it, centred. |
| 5 | **Popular banner** | A **24px** `primary` strip across the top of the middle tile, sharing the tile's top corners, with a 12px ★ + **POPULAR** in `label`, `white`. It highlights the tile but doesn't select it. |
| 6 | **Custom amount** | 16px below the tiles. "Enter Custom Amount" as an underlined `primary` Text button in `subtitle-base`, centred, with a 48px touch target. Tapping it replaces the link with a **text field** (standard 56px Text Field with a ₹ prefix). |
| 7 | **Footer** | 24px below the content, with a 1px `black-1` divider on top and 16px padding (plus the device safe area). It holds a full-width (343px) **Large** primary CTA. |

**States**

| State | Tiles | CTA |
|---|---|---|
| **Select amount** (initial) | No tile selected. All tiles are `white` with a `black-2` border; the Popular tile shows only its banner. | **Disabled** (`primary` at 38% opacity), labelled **"Select an amount"** |
| **Selected** | The chosen tile fills with `primary` and its border drops. Text turns `white`, with "per month" at 80% opacity. On a selected Popular tile, the banner becomes **`primary` at reduced opacity (80%)**, so it reads lighter than the fill. | **Enabled** (`primary`), labelled with the amount: **"Pay ₹300/mo →"** |

**Rules**
- Offer **three preset amounts**, with the middle one flagged **Popular**.
- **Nothing is pre-selected.** The CTA stays disabled and reads "Select an amount" until the donor chooses one.
- Once selected, the CTA label shows the amount and the billing period ("/mo").
- Amounts follow the [Indian number format](#number--currency-format).
- **Custom amount limits:** Default to ₹100 (minimum) and ₹300 (maximum) unless otherwise specified. Always confirm project-specific limits before executing. Before starting any project that involves a donation flow, ask: **"What are the minimum and maximum custom donation amounts?"**

### Icon Buttons
- Circular. Three sizes: 60px, 48px, and 32px buttons, with 24px, 20px, and 16px icons respectively.
- **Styles:** Filled (`primary`), Tonal (`primary-light`), Outlined (`black-2` border), and Standard (no container, the most common).
- **Toggles** (e.g. *favourite*): the icon switches from outlined to filled, in `primary`.
- Always give an icon button an accessible label.

### Chips
- 32px tall, `full` radius, 12px horizontal padding, `black-2` border, `subtitle-sm` label, 8px apart.
- **Types:** Assist (with a leading icon), Filter (selected = `primary-light` fill with ✓), Input (trailing ✕), Suggestion (e.g. donation amounts).

### Cards
- **Outlined** is the default (`white` + `black-2` border). **Filled** uses `black-1`. **Floating** uses the float shadow and is for special cases only.
- Radius follows Roundness; padding 16px; widths follow Element Widths.
- Media fills the top of the card edge to edge.

### Text Fields
- **Outlined**, 56px tall, 16px radius and padding.
- **Border:** `black-3` at rest; 2px `primary` on focus; 2px `error` when invalid.
- **Label:** `body-base` in `black-4`, floating to `body-sm` on focus. **Value:** `body-lg` in `black-5`.
- **Helper / error text:** `body-sm`, 4px below the field. Error messages say how to fix the problem.
- Prefixes (e.g. **₹**) sit inside the field.

### Selection Controls
- **Checkbox:** 18px, 2px radius; checked = `primary` fill with a white ✓.
- **Radio button:** 20px; selected = `primary` ring with a dot.
- **Switch:** 52 × 32 track; on = `primary` track with a white handle.
- **Touch target:** at least 48px for all controls.

### Progress
- **Linear:** 4px, `primary` on a `primary-light` track, `full` radius.
- **Circular:** 48px with a 4px stroke.
- Use `success` or `intermediate` only when you need to show a status.

### Badges
- **Dot:** 6px `error`.
- **Count:** 16px tall, `error` fill, `tag-xsmall-bold` in white, max "999+".

### Snackbars
- `black-6` surface, `body-base` text in `white`, 8px radius, float shadow.
- One optional action as a text button in `primary-light`.
- Show for 4–10 seconds.

### Dialogs
- `white` surface, 24px radius and padding, over the scrim.
- Title in `h5`, body in `body-base` (`black-4`), actions as text buttons aligned right.
- Destructive dialogs use an exact verb (e.g. *Delete*) in the danger colour.

### Bottom Sheets
- `white` surface, 24px top corners, a 32 × 4 `black-2` drag handle, 16px padding.
- Use for sharing, amount pickers and payment methods.

### Top App Bar
- 64px tall, `white` surface, `h6` title, a leading ← icon and up to 3 trailing icon buttons.
- Separated from content by a `black-1` divider once the page scrolls.

### Navigation Bar
- 80px tall, `white` surface, 3–5 destinations, 24px icons with `tag-xsmall-bold` labels.
- **Active destination:** a 64 × 32 `primary-light` pill with a filled icon; the label in `primary`.

### Tabs
- 48px tall, `subtitle-base` labels.
- **Active tab:** `primary` label and a 3px `primary` indicator. Inactive tabs are `black-4`.

### Lists
- Items are 56, 72 or 88px tall (one, two or three lines), with 16px padding.
- Headline in `body-lg`, supporting text in `body-base` (`black-4`).
- Optional inset `black-1` dividers.

### Menus & Tooltips
- **Menu:** `white` surface, 16px radius, float shadow, 48px items in `body-base`.
- **Plain tooltip:** `black-6` surface, `body-sm` in `white`, 8px radius.

---

## Number & Currency Format

**Ketto always uses the Indian number system: lakhs and crores.** Never use millions or billions (M, B), anywhere in the app, on the web or in marketing.

**Full numbers** use Indian digit grouping: the first comma after 3 digits, then every 2 digits.

| ✅ Do | ❌ Don't |
|---|---|
| ₹12,34,567 | ₹1,234,567 |
| ₹56,902 | ₹56902 |

**Abbreviated numbers** are for compact spaces: donor and supporter counts, card stats, and totals in headlines.

| Range | Format | Example |
|---|---|---|
| < 1,000 | Full number | 850 |
| 1,000 – 99,999 | k | 50k |
| 1,00,000 – 99,99,999 | L (lakh) | 22L, 1.5L |
| ≥ 1,00,00,000 | Cr (crore) | 3Cr, 1.2Cr |

- Use **at most one decimal**, and drop a trailing ".0" (write 2L, not 2.0L).
- **No space** between the number and its unit (22L, not 22 L).
- **Currency:** the ₹ symbol comes before the number with no space (₹56,902).
- **Exact money amounts** (amount left to raise, donation amounts, receipts, payment screens) always use the **full** number with Indian grouping. Don't abbreviate them.
- In running text, the words "lakh" and "crore" can be spelled out (e.g. "raised over ₹2 crore").

---

## Responsive Behavior

| Name | Width | Key changes |
|---|---|---|
| Mobile (app + web) | < 768px | 12-column mobile grid, 16px margins; cards stack or use carousels; bottom navigation bar; sticky donate bar on campaign pages |
| Desktop web | ≥ 768px | 12 columns with 24px gutters, max 1440px content width; multi-column card grids; top navigation |

### Touch Targets
- At least **48 × 48px** for anything tappable. Small buttons (32px tall) and small icon buttons need extra hit area around them.

---

## Accessibility
- **Contrast:** body text needs at least 4.5:1. Use `black-5` or `black-4` on `white`, and `primary-hover` for small teal text.
- **Focus:** every interactive element shows the 2px `primary` focus ring.
- **Colour alone:** never show a state with colour alone; pair it with an icon or text.
- **Motion:** respect `prefers-reduced-motion`.

---

## Known Gaps

- **Primary button contrast:** white on `primary` (#288B91) is **4.0:1**, below WCAG AA (4.5:1) for button label sizes. This is a known, accepted gap for now.
- **Desktop side margins:** not yet defined for the ≥768px grid.
- **`success` = `green-3`:** the same hex value. Decide whether they should stay linked or diverge.
- **`error-light` (#FDE7E9):** derived, not yet in the Figma palette.
- **Shadow value:** the single float shadow is confirmed as an approach; the exact value is derived.
- **Motion:** no Ketto motion spec exists yet. Default to MD3 standard easing (`cubic-bezier(0.2,0,0,1)`, 200–300ms).
- **Iconography:** the icon set, style and stroke aren't documented.
- **Amount Picker sizes:** the tile size, spacing, text styles and the 80% banner opacity are best guesses from the system. Check them against Figma.
- **Product components:** the rest of the Donate flow (tip, payment) and SIP subscription management still need screens.
- **MD3-based components:** Icon Buttons through Menus & Tooltips are adapted from Material Design 3 and should be replaced by Ketto designs over time.
- **Dark mode:** not defined.
- **Loading and skeleton states:** not defined.

### Fixed
- ✅ **Roundness boundary:** clarified as 110px (was ambiguous at 100px)
- ✅ **Typography:** merged `label-1` and `label-2` into single `label` token
- ✅ **Icon button sizes:** locked at 24px, 20px, 16px per button size (60px, 48px, 32px)
- ✅ **Cause card measurements:** width 255px (Large), height 310px, padding 16px, image 265×165px fixed, badge 48×18px, donor count in Indian format
- ✅ **Custom donation limits:** default to ₹100–₹300, confirm per project
