---
name: Xtreme Design
colors:
  surface: '#131411'
  surface-dim: '#131411'
  surface-bright: '#393936'
  surface-container-lowest: '#0e0e0c'
  surface-container-low: '#1c1c19'
  surface-container: '#20201d'
  surface-container-high: '#2a2a27'
  surface-container-highest: '#353532'
  on-surface: '#e5e2dd'
  on-surface-variant: '#e4beb1'
  inverse-surface: '#e5e2dd'
  inverse-on-surface: '#31302d'
  outline: '#ab897d'
  outline-variant: '#5b4137'
  surface-tint: '#ffb59a'
  primary: '#ffb59a'
  on-primary: '#5a1b00'
  primary-container: '#ff5c00'
  on-primary-container: '#521800'
  inverse-primary: '#a73a00'
  secondary: '#c7c4d7'
  on-secondary: '#2f2f3d'
  secondary-container: '#464555'
  on-secondary-container: '#b5b3c6'
  tertiary: '#bac3ff'
  on-tertiary: '#00218d'
  tertiary-container: '#738aff'
  on-tertiary-container: '#001d81'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffdbce'
  primary-fixed-dim: '#ffb59a'
  on-primary-fixed: '#370e00'
  on-primary-fixed-variant: '#802a00'
  secondary-fixed: '#e3e0f4'
  secondary-fixed-dim: '#c7c4d7'
  on-secondary-fixed: '#1a1a28'
  on-secondary-fixed-variant: '#464555'
  tertiary-fixed: '#dee1ff'
  tertiary-fixed-dim: '#bac3ff'
  on-tertiary-fixed: '#001159'
  on-tertiary-fixed-variant: '#0332c3'
  background: '#131411'
  on-background: '#e5e2dd'
  surface-variant: '#353532'
typography:
  display-xl:
    fontFamily: EB Garamond
    fontSize: 80px
    fontWeight: '600'
    lineHeight: 88px
    letterSpacing: -0.02em
  display-xl-mobile:
    fontFamily: EB Garamond
    fontSize: 48px
    fontWeight: '600'
    lineHeight: 52px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: EB Garamond
    fontSize: 48px
    fontWeight: '500'
    lineHeight: 56px
  headline-lg-mobile:
    fontFamily: EB Garamond
    fontSize: 32px
    fontWeight: '500'
    lineHeight: 40px
  headline-md:
    fontFamily: Hanken Grotesk
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
    letterSpacing: 0.05em
  body-lg:
    fontFamily: Hanken Grotesk
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Hanken Grotesk
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-caps:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.1em
  quote-text:
    fontFamily: EB Garamond
    fontSize: 32px
    fontWeight: '400'
    lineHeight: 44px
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1440px
  gutter: 24px
  margin-mobile: 20px
  margin-desktop: 64px
  section-gap: 120px
---

## Brand & Style

This design system is built to reflect the high-impact, multi-faceted nature of an Indian branding and packaging powerhouse. The personality is **authoritative yet versatile**, designed to pivot between high-fashion editorial aesthetics and functional B2B reliability. 

The visual direction follows a **Modern Editorial** movement: a blend of high-contrast typography, precise grid alignment, and sophisticated tactile layers. It prioritizes the "Object as Hero" philosophy, ensuring that physical packaging mockups and brand assets are the focal points. The interface acts as a premium gallery—unobtrusive but structurally rigid, using deliberate whitespace to evoke a sense of luxury and scale.

**Target Audience:**
- Enterprise-level Indian FMCG brands.
- Boutique luxury startups.
- Global marketing directors looking for localized Indian expertise.

**Emotional Response:**
- Confidence in creative execution.
- Perception of premium quality.
- Ease of navigation through complex service offerings.

## Colors

The palette is engineered to support four distinct visual modes, with **Dark Navy (#0D0D1A)** and **Electric Orange (#FF5C00)** serving as the foundational brand identity. 

- **Primary Mode (Bold & Editorial):** Utilizes the deep navy background with electric orange as the high-energy "call to action" and navigational accent.
- **B2B Mode (Clean & Professional):** Shifts to white backgrounds with Cobalt Blue (#1A3ECC) for links and structural elements, ensuring accessibility and trust.
- **Creative Mode (Vibrant):** Employs the warm off-white (#FBF8F3) as a canvas for the Magenta/Coral (#E8305A) accents, softening the brand for lifestyle-oriented projects.
- **Minimal Mode:** Focuses on the Deep Forest Green (#1A4A2E) against near-white, providing a sophisticated, organic feel for eco-conscious packaging narratives.

System-wide status colors (success, error, warning) should be desaturated to maintain the premium editorial aesthetic.

## Typography

This system uses a tiered typographic strategy to balance "The Hook" (Editorial) with "The Detail" (Technical).

- **Display & Headlines:** Use **EB Garamond**. It provides a literary, high-fashion authority required for luxury packaging. Use optical sizing where available to keep thin serifs crisp.
- **Body & Interface:** Use **Hanken Grotesk**. It is a contemporary, sharp sans-serif that handles technical B2B data and long-form project descriptions with high legibility.
- **Technical Annotations:** Use **JetBrains Mono** for labels, category tags, and packaging specifications. This adds a "studio-process" feel, suggesting precision and craftsmanship.

**Hierarchy Note:** 
Always maintain a high contrast between display sizes and body text. Large headlines should be tightly tracked (-0.02em) to feel impactful.

## Layout & Spacing

The design system utilizes a **Rigid Editorial Grid**. 

- **Desktop (1440px+):** 12-column fluid grid with wide 64px outer margins. This creates "breathing room" reminiscent of premium coffee-table books.
- **Tablet (768px - 1024px):** 8-column grid with 40px margins.
- **Mobile (Under 768px):** 4-column grid with 20px margins.

**The "Power of Silence":** Spacing between major sections should be aggressive (120px+). Content should be grouped using the 8px base unit, but the gap between unrelated groups must be large enough to let the individual brand assets "own" the screen. Use asymmetrical layouts (e.g., content spanning columns 2-7, images spanning 8-12) to break the monotony of standard SaaS layouts.

## Elevation & Depth

To maintain the "Object as Hero" focus, elevation is achieved through **Tonal Layering** and **Ambient Depth** rather than traditional heavy shadows.

- **Surface Levels:** 
    - Level 0: Primary background (Navy or Off-White).
    - Level 1: Content tiles and cards using a subtle 2-3% lighter or darker shade than the background.
- **Shadows:** Use only for floating elements (modals, dropdowns). Shadows should be "Long & Soft"—low opacity (10%), high blur (40px), and tinted with the primary background color (#0D0D1A) to avoid a "dirty" gray look.
- **Glassmorphism:** Reserved exclusively for navigation bars and localized CTAs (like the WhatsApp float), using a 12px backdrop blur to maintain legibility over vibrant portfolio imagery.

## Shapes

The shape language is primarily **Structural and Sharp**. 

- **Standard Elements:** Use a subtle 0.25rem (`rounded-sm`) radius for buttons and input fields to maintain a professional edge.
- **Portfolio Tiles:** Should remain perfectly sharp (0px) to mimic physical printed packaging samples.
- **Creative Mode Exception:** When the "Vibrant & Creative" mode is active, the system may scale up to `rounded-lg` (1rem) for specific lifestyle badges and chips to evoke a friendlier, consumer-facing feel.
- **Icons:** Use thin-stroke (1.5pt) linear icons with square caps to match the technicality of the typography.

## Components

### Packaging-Specific UI
- **Mockup Tiles:** Full-bleed image containers with a 1px inner border. On hover, display the `label-caps` typography showing substrate type (e.g., "350GSM MATTE CARDBOARD").
- **Category Badges:** Small, rectangular badges using `label-caps`. Backgrounds should use the secondary or accent colors depending on the brand mode.

### Professional B2B Elements
- **Stats Strips:** Horizontal dividers with high-contrast `headline-lg` numbers and `body-md` descriptions, separated by 1px vertical lines.
- **Testimonial Blocks:** Large `quote-text` in EB Garamond, centered, with a small mono-spaced label for the client’s name and designation below.
- **Quote CTAs:** Bold, full-width strips using the Electric Orange background. Use `headline-md` for the text to create urgency.

### Indian-Market Cues
- **WhatsApp Integration:** A persistent floating action button (FAB) in the bottom right. Use a blurred glass container with the official WhatsApp green icon, but styled to fit the 1.5pt stroke weight of the system.
- **Localized Brand References:** UI placeholders for "FSSAI Compliance" or "Make in India" seals, treated with the same mono-spaced technical styling to look integrated rather than like external stickers.

### Input Fields & Controls
- **Fields:** Bottom-border only (underline style) for a minimalist, "form-like" aesthetic. 
- **Buttons:** Primary buttons are solid (Orange or Blue) with `label-caps` text. Secondary buttons are "Ghost" style with a 1px border.