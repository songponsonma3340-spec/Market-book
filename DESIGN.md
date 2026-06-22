---
name: Luminous Verve
colors:
  surface: '#121414'
  surface-dim: '#121414'
  surface-bright: '#38393a'
  surface-container-lowest: '#0c0f0f'
  surface-container-low: '#1a1c1c'
  surface-container: '#1e2020'
  surface-container-high: '#282a2b'
  surface-container-highest: '#333535'
  on-surface: '#e2e2e2'
  on-surface-variant: '#c6c9ad'
  inverse-surface: '#e2e2e2'
  inverse-on-surface: '#2f3131'
  outline: '#909379'
  outline-variant: '#454933'
  surface-tint: '#b8d300'
  primary: '#ffffff'
  on-primary: '#2c3400'
  primary-container: '#d2f018'
  on-primary-container: '#5c6b00'
  inverse-primary: '#576500'
  secondary: '#e9c176'
  on-secondary: '#412d00'
  secondary-container: '#604403'
  on-secondary-container: '#dab36a'
  tertiary: '#ffffff'
  on-tertiary: '#313030'
  tertiary-container: '#e5e2e1'
  on-tertiary-container: '#656464'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#d2f018'
  primary-fixed-dim: '#b8d300'
  on-primary-fixed: '#191e00'
  on-primary-fixed-variant: '#414c00'
  secondary-fixed: '#ffdea5'
  secondary-fixed-dim: '#e9c176'
  on-secondary-fixed: '#261900'
  on-secondary-fixed-variant: '#5d4201'
  tertiary-fixed: '#e5e2e1'
  tertiary-fixed-dim: '#c8c6c5'
  on-tertiary-fixed: '#1c1b1b'
  on-tertiary-fixed-variant: '#474646'
  background: '#121414'
  on-background: '#e2e2e2'
  surface-variant: '#333535'
typography:
  display-lg:
    fontFamily: Syne
    fontSize: 64px
    fontWeight: '800'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Syne
    fontSize: 40px
    fontWeight: '800'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Syne
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
  body-lg:
    fontFamily: Hanken Grotesk
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-sm:
    fontFamily: Hanken Grotesk
    fontSize: 14px
    fontWeight: '400'
    lineHeight: '1.5'
  label-caps:
    fontFamily: Geist
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: 0.1em
  mono-admin:
    fontFamily: Geist
    fontSize: 13px
    fontWeight: '500'
    lineHeight: '1.4'
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1440px
  gutter: 24px
  margin-desktop: 64px
  margin-mobile: 20px
---

## Brand & Style
The brand personality is premium, energetic, and sophisticated, targeting a high-achieving demographic that values both aesthetic beauty and functional precision. The design style is **Glassmorphism mixed with High-Contrast Boldness**. It utilizes deep obsidian surfaces layered with translucent glass cards to create a sense of infinite depth.

For the "Illuminator" tier, the UI transitions into a more prestigious state. This is achieved through the introduction of metallic gold accents, micro-shimmer animations on interactive borders, and high-fidelity iconography. The emotional response should be one of exclusive access and "enlightened" productivity. Administrative areas remain grounded and utilitarian but retain the high-contrast clarity of the core brand.

## Colors
This design system defaults to a **dark mode** architecture.
- **Primary:** An electric "Volt" yellow-green (#E0FF2E) used for standard calls to action and primary brand moments.
- **Secondary (Illuminator):** A muted, sophisticated gold (#C5A059) used for high-tier navigation and premium status indicators.
- **Tertiary/Base:** A deep "Obsidian" (#0F0F0F) which acts as the canvas for all glass effects.
- **Neutral:** High-purity whites and grays for maximum legibility against dark backgrounds.

The **Illuminator Tier** uses a specific hex (#FFD700) for "True Gold" accents, often applied as 1px borders or linear gradients to simulate light reflection.

## Typography
The typography strategy pairs the avant-garde, expressive nature of **Syne** for headlines with the clinical precision of **Hanken Grotesk** for body copy. 

For administrative controls and subscription data, **Geist** is used to provide a technical, developer-friendly feel that ensures data density is readable and organized. Large display titles should always use tight letter spacing and heavy weights to anchor the glassmorphic layouts.

## Layout & Spacing
The design system utilizes a **fluid grid** with a maximum container width of 1440px. A 12-column structure is used for desktop, collapsing to 4 columns for mobile. 

Spacing follows a strict 8px linear scale. For administrative views (Subscription Management), the density increases—gutters are reduced to 16px to allow for side-by-side data comparisons and complex control panels. Illuminator-exclusive pages utilize more generous whitespace ("luxury margins") to emphasize the premium nature of the content.

## Elevation & Depth
Depth is created through **Glassmorphism** and **Ambient Shadows**.
- **Level 1 (Base):** Obsidian background.
- **Level 2 (Standard Card):** Semi-transparent black (40% opacity) with a 1px stroke (10% white) and 20px backdrop blur.
- **Level 3 (Illuminator Card):** Semi-transparent gold-tinted black (50% opacity) with a dual stroke: a 1px "True Gold" outer border and a soft inner "shimmer" glow.
- **Level 4 (Modals/Popovers):** High-contrast glass with deep 40px blurs and a shadow cast of `0 20px 50px rgba(0,0,0,0.5)`.

Illuminator elements feature a "shimmer" effect—a diagonal linear gradient highlight that moves across the surface on hover or page load.

## Shapes
The shape language is **Rounded**, favoring 0.5rem (8px) as the base radius. 

While standard components use this 8px radius, **Illuminator badges and high-tier buttons** often employ "Pill-shaped" geometry to distinguish them from the more structural, rectangular administrative elements. Input fields in the subscription management area maintain the standard 8px radius for a professional, systematic look.

## Components
### Buttons
- **Primary:** High-contrast Volt (#E0FF2E) with black text. Sharp 8px corners.
- **Illuminator:** Gold gradient background with a subtle "shimmer" CSS animation. Uses the "Pill" shape.
- **Admin/Action:** Ghost buttons with 1px Geist-style borders.

### Cards & Containers
- **Standard:** Glassmorphic with 20px blur.
- **Premium (Illuminator):** Features a "Gold Leaf" icon in the top right and a 1px gold border.
- **Admin Panel:** Solid surfaces (no transparency) to ensure maximum focus on data integrity.

### Subscription Management (Admin)
- **Status Chips:** Small, condensed labels using `label-caps`. 
- **Toggle Switches:** Minimalist, using the Primary Volt color for "On" states.
- **Data Tables:** Borderless with subtle row separators (5% white) and hover states that utilize a low-opacity Volt tint.

### Iconography
- **Standard:** Linear, 2px stroke weight.
- **Illuminator:** Duotone gold and white icons with "glowing" focal points.