---
name: Fiel Companion System
colors:
  surface: '#fff8f6'
  surface-dim: '#fad1ca'
  surface-bright: '#fff8f6'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#fff0ee'
  surface-container: '#ffe9e6'
  surface-container-high: '#ffe2dd'
  surface-container-highest: '#ffdad4'
  on-surface: '#2b1612'
  on-surface-variant: '#55433a'
  inverse-surface: '#432a26'
  inverse-on-surface: '#ffedea'
  outline: '#887369'
  outline-variant: '#dbc1b6'
  surface-tint: '#984714'
  primary: '#91430f'
  on-primary: '#ffffff'
  primary-container: '#b05a26'
  on-primary-container: '#fff6f3'
  inverse-primary: '#ffb690'
  secondary: '#7c516b'
  on-secondary: '#ffffff'
  secondary-container: '#fec8e6'
  on-secondary-container: '#7a506a'
  tertiary: '#705500'
  on-tertiary: '#ffffff'
  tertiary-container: '#8c6d19'
  on-tertiary-container: '#fff6ea'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdbca'
  primary-fixed-dim: '#ffb690'
  on-primary-fixed: '#341100'
  on-primary-fixed-variant: '#783200'
  secondary-fixed: '#ffd8ec'
  secondary-fixed-dim: '#ecb7d5'
  on-secondary-fixed: '#300f26'
  on-secondary-fixed-variant: '#613a52'
  tertiary-fixed: '#ffdf98'
  tertiary-fixed-dim: '#e8c266'
  on-tertiary-fixed: '#251a00'
  on-tertiary-fixed-variant: '#5a4300'
  background: '#fff8f6'
  on-background: '#2b1612'
  surface-variant: '#ffdad4'
typography:
  headline-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Nunito Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Nunito Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: Nunito Sans
    fontSize: 14px
    fontWeight: '700'
    lineHeight: 20px
  label-sm:
    fontFamily: Nunito Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 4px
  xs: 8px
  sm: 16px
  md: 24px
  lg: 48px
  xl: 80px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 64px
---

## Brand & Style

The design system for Petshop Mi Amigo Fiel is rooted in the concept of "The Trusted Local Neighbor." It balances professional retail standards with the warmth of a community pet shop in Monte Castro. The target audience includes pet owners who view their animals as family members and seek a reliable, welcoming environment for their care.

The visual style is **Corporate / Modern** with a **Tactile** twist. It utilizes clean layouts and high-quality whitespace to ensure professionalism, while incorporating soft, organic shapes and pill-shaped elements to evoke a pet-friendly, approachable atmosphere. The interaction model is designed to be "squishy" and inviting—using generous radiuses and subtle depth to make every digital touchpoint feel as comfortable as a local shop visit.

## Colors

This color palette is designed to mirror the natural tones of pets (Rich Brown) and the playful energy of the shop's brand (Soft Pink and Golden Yellow).

- **Primary (Rich Brown):** Used for primary actions, headings, and branding elements to establish authority and warmth.
- **Secondary (Soft Pink):** Derived from the logo's background blob, this is used for decorative elements, soft backgrounds for cards, and non-critical accents.
- **Accent (Golden Yellow):** Reserved specifically for high-visibility CTAs, "New" badges, and promotional highlights to ensure they pop against the white and brown tones.
- **Neutrals:** Pure White (#FFFFFF) provides a clean canvas, while High-Contrast Black (#050000) ensures maximum legibility for body copy and labels.

## Typography

This design system employs two distinct sans-serif families to balance modernity with approachability.

- **Plus Jakarta Sans** is used for all headlines. Its slightly wider stance and friendly terminals provide a contemporary retail feel that is highly legible.
- **Nunito Sans** is used for body copy and labels. Its naturally rounded characters harmonize perfectly with the "pet-friendly" aesthetic and ensure comfort during long reading sessions, such as pet care blogs or product descriptions.

Typography scales are generous to accommodate older users or those seeking a quick glance at prices and services.

## Layout & Spacing

The design system utilizes a **Fluid Grid** with fixed maximum widths for desktop to maintain readability. 

- **Desktop:** 12-column grid, 1200px max-width, 24px gutters.
- **Tablet:** 8-column grid, 24px gutters, 32px side margins.
- **Mobile:** 4-column grid, 16px gutters, 16px side margins.

Spacing follows an 8pt rhythm for structural elements, with a 4pt scale for internal component padding. Vertical rhythm is relaxed, emphasizing whitespace to prevent the UI from feeling cluttered or "noisy," which can be stressful for users.

## Elevation & Depth

To maintain the "Modern & Soft" style, this design system avoids harsh shadows. Instead, it uses **Ambient Shadows** and **Tonal Layers**.

1. **Level 0 (Flat):** Main background (#FFFFFF).
2. **Level 1 (Subtle):** Cards and containers use a very soft shadow (0px 4px 20px rgba(176, 90, 38, 0.08))—a brown-tinted shadow that feels warmer than neutral grey.
3. **Level 2 (Floating):** Navigation bars and active CTAs use a more pronounced shadow (0px 8px 30px rgba(176, 90, 38, 0.12)) to indicate interactivity.
4. **Interactive States:** Buttons use a slight inner shadow on click to simulate a "physical" press, reinforcing the tactile feel.

## Shapes

The shape language is consistently **Rounded**. There are no sharp corners in this design system. 

- **Standard Elements (Buttons, Inputs):** 0.5rem (8px) radius.
- **Large Containers (Cards, Modals):** 1.5rem (24px) radius.
- **Decorative Accents:** Use "blob" shapes inspired by the logo's background to frame images of animals, creating a soft, organic look that breaks the rigidity of the grid.

## Components

### Buttons
- **Primary:** Rich Brown (#B05A26) with White text. Bold, rounded-lg.
- **CTA/Urgent:** Golden Yellow (#E4BE63) with Black text. Used for "Buy Now" or "Book Grooming."
- **Secondary:** Soft Pink (#E3AFCC) with Brown text. Used for "Learn More" or "View All."

### Cards
Cards feature a 1px border in a lightened tint of Brown (5% opacity) and a Level 1 shadow. Image headers within cards should have a top-only radius to match the container.

### Input Fields
Inputs use a soft grey border (1px) that turns Rich Brown on focus. Labels are always positioned above the field in Nunito Sans Bold for maximum clarity.

### Chips & Badges
Small, pill-shaped markers used for "In Stock," "Dog," "Cat," or "Discount." Use the Golden Yellow background for discounts and Soft Pink for categories.

### Specific Product Components
- **Pet Profiles:** Circular avatars for "My Pets" sections.
- **Service Cards:** Large, icon-heavy cards for Grooming, Pharmacy, and Shop, using the primary brown for iconography.