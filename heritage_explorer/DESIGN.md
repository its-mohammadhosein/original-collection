---
name: Heritage Explorer
colors:
  surface: '#fbf9f6'
  surface-dim: '#dbdad7'
  surface-bright: '#fbf9f6'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f3f0'
  surface-container: '#efeeeb'
  surface-container-high: '#e9e8e5'
  surface-container-highest: '#e3e2e0'
  on-surface: '#1b1c1a'
  on-surface-variant: '#434843'
  inverse-surface: '#30312f'
  inverse-on-surface: '#f2f1ee'
  outline: '#737973'
  outline-variant: '#c3c8c1'
  surface-tint: '#4d6453'
  primary: '#061b0e'
  on-primary: '#ffffff'
  primary-container: '#1b3022'
  on-primary-container: '#819986'
  inverse-primary: '#b4cdb8'
  secondary: '#78582b'
  on-secondary: '#ffffff'
  secondary-container: '#ffd39b'
  on-secondary-container: '#79592c'
  tertiary: '#271013'
  on-tertiary: '#ffffff'
  tertiary-container: '#3f2427'
  on-tertiary-container: '#b0898c'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d0e9d4'
  primary-fixed-dim: '#b4cdb8'
  on-primary-fixed: '#0b2013'
  on-primary-fixed-variant: '#364c3c'
  secondary-fixed: '#ffddb4'
  secondary-fixed-dim: '#eabf89'
  on-secondary-fixed: '#291800'
  on-secondary-fixed-variant: '#5e4116'
  tertiary-fixed: '#ffd9dc'
  tertiary-fixed-dim: '#e7bcbf'
  on-tertiary-fixed: '#2d1417'
  on-tertiary-fixed-variant: '#5d3f42'
  background: '#fbf9f6'
  on-background: '#1b1c1a'
  surface-variant: '#e3e2e0'
  slate-gray: '#4A5553'
  warm-stone: '#F4F1ED'
  dark-charcoal: '#1A1A1A'
  ochre-accent: '#D4A373'
typography:
  display-lg:
    fontFamily: Libre Caslon Text
    fontSize: 64px
    fontWeight: '400'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Libre Caslon Text
    fontSize: 40px
    fontWeight: '400'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Libre Caslon Text
    fontSize: 32px
    fontWeight: '400'
    lineHeight: '1.3'
  headline-sm:
    fontFamily: Libre Caslon Text
    fontSize: 24px
    fontWeight: '400'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Hanken Grotesk
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Hanken Grotesk
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-caps:
    fontFamily: Hanken Grotesk
    fontSize: 12px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: 0.1em
  navigation:
    fontFamily: Hanken Grotesk
    fontSize: 14px
    fontWeight: '500'
    lineHeight: '1.0'
    letterSpacing: 0.05em
spacing:
  unit: 8px
  container-max: 1280px
  gutter: 24px
  margin-desktop: 64px
  margin-mobile: 20px
  section-padding: 120px
---

## Brand & Style

This design system embodies the spirit of a "curator of memories," blending the rugged, storied history of Scottish heritage with the refined precision of modern luxury hospitality. The brand personality is sophisticated yet adventurous—equally at home in a grand castle ballroom as it is on a windswept Highland coast.

The visual style is **Editorial Minimalism**. It prioritizes high-impact, immersive photography as the primary storytelling vehicle, supported by an expansive use of whitespace and a rigorous typographic hierarchy. By avoiding unnecessary decorative flourishes, the design system allows the unique character of each property to remain the focus, evoking an emotional response of calm, curiosity, and exclusivity. 

Key stylistic pillars include:
- **Authentic Textures:** Subtle grain and paper-like backgrounds that suggest physical ephemera.
- **Modern Heritage:** Pairing traditional serif letterforms with a high-performance, utilitarian sans-serif.
- **Curated Grid:** A structured yet flexible layout that mimics high-end travel journals and broadsheet newspapers.

## Colors

The palette is rooted in the natural landscapes of the British Isles. The primary **Forest Green** serves as the anchor, representing stability and heritage. **Rich Ochre** is used sparingly for primary actions and accents, providing a warm contrast that feels sun-drenched and premium.

**Neutral Framework:**
- **Backgrounds:** Primarily `warm-stone` for a softer, more inviting feel than pure white, reducing eye strain and enhancing the "boutique" aesthetic.
- **Typography:** `dark-charcoal` is the default for body text to ensure maximum readability and WCAG AA compliance.
- **Secondary UI:** `slate-gray` is utilized for secondary information, dividers, and borders to maintain a low-visual-noise environment.

## Typography

The typographic strategy balances **Libre Caslon Text**, a serif with historical weight and elegant curves, with **Hanken Grotesk**, a sharp and modern sans-serif. 

**Usage Guidelines:**
- **Serif (Headlines):** Used for storytelling and property names. It should never be used for functional labels or small metadata.
- **Sans-Serif (Body & Nav):** Ensures high performance and clarity. Large blocks of text should always use `body-md` or `body-lg` to maintain accessibility.
- **Character:** Use `label-caps` for eyebrows and category tags to create a rhythmic "magazine" feel.
- **Spacing:** Generous line-heights are mandatory to prevent visual crowding and maintain the minimalist aesthetic.

## Layout & Spacing

The design system employs a **12-column fixed grid** for desktop, transitioning to a **4-column fluid grid** for mobile. The layout philosophy is "breathing room"—sections are separated by significant vertical padding to emphasize the curated nature of the content.

**Key Principles:**
- **Asymmetric Balance:** Elements may span different column widths (e.g., a 7-column image paired with a 4-column text block) to create visual interest.
- **Immersive Hero:** Primary imagery should often break the container or span the full viewport width to draw the user into the destination.
- **The "Pipe" Divider:** Use vertical lines (`|`) with 16px of horizontal spacing to separate metadata in headers and footers, echoing the brand's established visual shorthand.

## Elevation & Depth

This design system avoids heavy drop shadows in favor of **Tonal Layering** and **Low-Contrast Outlines**.

- **Surfaces:** Depth is achieved by placing `warm-stone` containers against white backgrounds, or `forest-green` sections against `warm-stone`.
- **Borders:** Use very fine, 1px borders in `slate-gray` (at 20% opacity) to define functional areas like input fields or card boundaries without adding visual weight.
- **Interactive States:** Lift elements slightly using a subtle, highly-diffused shadow (Blur: 20px, Opacity: 5%) only upon hover to provide tactile feedback while maintaining a flat, sophisticated appearance.

## Shapes

The shape language is strictly **Sharp (0px)**. 

To reflect the architectural heritage of castles and the precision of high-end design, all UI elements—including buttons, cards, images, and input fields—utilize 90-degree corners. This creates a sense of structure, strength, and timelessness. The only exception is the use of circular icons or profile images where strictly necessary for standard UI patterns.

## Components

**Buttons**
- **Primary:** Solid `dark-charcoal` background with white `navigation` text. Sharp corners. Hover state shifts to `primary-color-hex` (Forest Green).
- **Secondary:** Transparent background with a 1px `dark-charcoal` border.
- **Ghost/Link:** `label-caps` text followed by the signature `| ->` arrow glyph.

**Cards**
- Cards should be borderless with generous internal padding. 
- Use high-aspect-ratio imagery (e.g., 3:4 or 4:5) to give property listings a vertical, editorial feel.
- Typography within cards must follow the hierarchy: Serif for the name, Sans-Serif for the location.

**Input Fields**
- Minimalist design: A single bottom border in `slate-gray` instead of a full box, creating a cleaner, more sophisticated form experience.
- Labels use `label-caps` and sit above the field.

**Navigation**
- A "sticky" top bar that transitions from transparent to `warm-stone` on scroll. 
- The "Book Now" call-to-action should be a prominent, dark rectangular button centered or right-aligned to drive conversion without breaking the minimalist flow.