---
name: Obsidian Kinetic
colors:
  surface: '#051424'
  surface-dim: '#051424'
  surface-bright: '#2c3a4c'
  surface-container-lowest: '#010f1f'
  surface-container-low: '#0d1c2d'
  surface-container: '#122131'
  surface-container-high: '#1c2b3c'
  surface-container-highest: '#273647'
  on-surface: '#d4e4fa'
  on-surface-variant: '#b9cacb'
  inverse-surface: '#d4e4fa'
  inverse-on-surface: '#233143'
  outline: '#849495'
  outline-variant: '#3b494b'
  surface-tint: '#00dbe9'
  primary: '#dbfcff'
  on-primary: '#00363a'
  primary-container: '#00f0ff'
  on-primary-container: '#006970'
  inverse-primary: '#006970'
  secondary: '#70d6e0'
  on-secondary: '#00363b'
  secondary-container: '#2f9fa9'
  on-secondary-container: '#002f33'
  tertiary: '#f9f5f5'
  on-tertiary: '#313030'
  tertiary-container: '#dcd9d8'
  on-tertiary-container: '#605f5e'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#7df4ff'
  primary-fixed-dim: '#00dbe9'
  on-primary-fixed: '#002022'
  on-primary-fixed-variant: '#004f54'
  secondary-fixed: '#8df2fd'
  secondary-fixed-dim: '#70d6e0'
  on-secondary-fixed: '#002023'
  on-secondary-fixed-variant: '#004f55'
  tertiary-fixed: '#e5e2e1'
  tertiary-fixed-dim: '#c8c6c5'
  on-tertiary-fixed: '#1c1b1b'
  on-tertiary-fixed-variant: '#474646'
  background: '#051424'
  on-background: '#d4e4fa'
  surface-variant: '#273647'
typography:
  headline-xl:
    fontFamily: Geist
    fontSize: 48px
    fontWeight: '600'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-xl-mobile:
    fontFamily: Geist
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Geist
    fontSize: 32px
    fontWeight: '500'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Geist
    fontSize: 24px
    fontWeight: '500'
    lineHeight: 32px
    letterSpacing: -0.01em
  body-md:
    fontFamily: Geist
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Geist
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-code:
    fontFamily: JetBrains Mono
    fontSize: 13px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.05em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base: 8px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 64px
  max-width: 1440px
---

## Brand & Style
The design system targets a high-end technical audience, blending the precision of developer tools with the exclusivity of a luxury brand. The aesthetic is a fusion of **Minimalism** and **Glassmorphism**, creating a high-fidelity environment that feels both advanced and breathable.

The interface should evoke a sense of "quiet power"—fast, responsive, and deeply sophisticated. It utilizes expansive whitespace, meticulous typography, and subtle motion to convey a premium, high-tech experience.

## Colors
The palette is rooted in a deep "Obsidian" dark mode. The **Primary Cyan** (#00f0ff) serves as a high-energy "electric" accent for critical actions and active states. The **Secondary Teal** (#008a94) provides a sophisticated, grounded counterpoint, used for supporting elements and secondary interactive states to maintain a monochromatic, high-tech harmony.

Surface colors utilize varying levels of dark greys and blacks to create depth without relying on pure black, ensuring gradients and blurs remain rich and legible.

## Typography
The system uses **Geist** for its clinical precision and modern Swiss-inspired proportions, ensuring readability across complex technical data. **JetBrains Mono** is reserved for metadata, labels, and technical values to reinforce the high-tech narrative.

All typography should prioritize clarity. Headlines utilize tight letter-spacing for a "machined" look, while body text maintains standard tracking for optimal long-form reading.

## Layout & Spacing
The layout follows a **Fluid Grid** model based on an 8px square-grid system. On desktop, a 12-column structure is used with generous 64px outer margins to create a focused "stage" for content.

As the viewport scales down to mobile, margins reduce to 16px and the layout collapses to a single-column flow. Spacing between sections should be aggressive (80px+) to maintain the minimalist, luxury feel of the brand.

## Elevation & Depth
Depth is achieved through **Glassmorphism** and **Tonal Layers** rather than traditional shadows. 

1. **Base:** The deepest layer, pure Obsidian.
2. **Plates:** Semi-transparent surfaces (10-15% opacity) with a 20px backdrop blur and a subtle 1px inner border (white at 10% opacity) to catch the "light."
3. **Floating:** For modals and tooltips, use a more opaque background with a very soft, large-radius glow tinted with the Primary Cyan at extremely low (5%) opacity.

## Shapes
The design system adopts a **Soft** (Level 1) roundedness. This provides a subtle nod to precision engineering—not as harsh as sharp 90-degree angles, but not as playful as fully rounded corners. This "engineered radius" maintains the professional and premium tone of the brand.

## Components
- **Buttons:** Primary buttons are solid Primary Cyan with black text. Secondary buttons are outlined with the Secondary Teal, using a "ghost" style that fills on hover.
- **Inputs:** Dark, recessed backgrounds with a 1px border. On focus, the border transitions to Primary Cyan with a subtle outer glow.
- **Cards:** Use the "Plates" elevation style. No shadows; depth is created via backdrop-blur and thin stroke dividers.
- **Chips:** Small, all-caps labels using JetBrains Mono, with a low-opacity background tint derived from the Secondary Teal.
- **Data Tables:** High-density, using subtle 1px horizontal lines. Row highlights use a 5% opacity Primary Cyan tint.
- **Status Indicators:** Use the Primary Cyan for "Active/Success" and the Secondary Teal for "Secondary/Neutral" statuses to keep the interface strictly within the defined high-tech family.