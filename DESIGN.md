---
name: Fiscal Prestige
colors:
  surface: '#f8f9fa'
  surface-dim: '#d9dadb'
  surface-bright: '#f8f9fa'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f4f5'
  surface-container: '#edeeef'
  surface-container-high: '#e7e8e9'
  surface-container-highest: '#e1e3e4'
  on-surface: '#191c1d'
  on-surface-variant: '#42474d'
  inverse-surface: '#2e3132'
  inverse-on-surface: '#f0f1f2'
  outline: '#73777e'
  outline-variant: '#c3c7ce'
  surface-tint: '#406182'
  primary: '#001629'
  on-primary: '#ffffff'
  primary-container: '#002b49'
  on-primary-container: '#7293b6'
  inverse-primary: '#a8caef'
  secondary: '#775a19'
  on-secondary: '#ffffff'
  secondary-container: '#fed488'
  on-secondary-container: '#785a1a'
  tertiary: '#001a06'
  on-tertiary: '#ffffff'
  tertiary-container: '#003111'
  on-tertiary-container: '#00a74c'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#cfe5ff'
  primary-fixed-dim: '#a8caef'
  on-primary-fixed: '#001d34'
  on-primary-fixed-variant: '#274969'
  secondary-fixed: '#ffdea5'
  secondary-fixed-dim: '#e9c176'
  on-secondary-fixed: '#261900'
  on-secondary-fixed-variant: '#5d4201'
  tertiary-fixed: '#66ff8e'
  tertiary-fixed-dim: '#3de273'
  on-tertiary-fixed: '#002109'
  on-tertiary-fixed-variant: '#005322'
  background: '#f8f9fa'
  on-background: '#191c1d'
  surface-variant: '#e1e3e4'
typography:
  display-lg:
    fontFamily: Montserrat
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Montserrat
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
  headline-md:
    fontFamily: Montserrat
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.05em
  headline-lg-mobile:
    fontFamily: Montserrat
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  container-max: 1200px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 48px
---

## Brand & Style

The design system is anchored in the principles of **Corporate Modernism**, blending the traditional authority of an established accounting firm with the clean, efficient aesthetic of a modern fintech platform. The brand personality is professional, meticulous, and reassuringly stable.

Key visual pillars include:
- **Clarity and Precision:** High-contrast typography and generous white space to ensure financial data and service descriptions are easily digestible.
- **Modern Trust:** Moving away from dated, heavy corporate templates in favor of a light, airy interface that utilizes soft depth and subtle gradients.
- **Approachable Authority:** The use of rounded geometric shapes softens the "serious" nature of accounting, making the firm feel accessible and client-focused while maintaining a premium positioning.

## Colors

The palette is designed to project stability and financial growth. 

- **Primary (Deep Petrol):** Used for navigation, headers, and primary branding elements. It provides the "anchor" for the visual identity.
- **Secondary (Soft Gold):** Used sparingly as a "solidity" accent—buttons, active icons, or high-value callouts—to evoke a sense of premium service and prosperity.
- **Semantic Green (WhatsApp):** A specific, high-visibility green reserved exclusively for the primary contact method to ensure immediate recognition.
- **Neutral/Backgrounds:** A tiered system of off-whites and cool grays ensures the interface feels light and open. Use white (#FFFFFF) for the main content areas and the light neutral (#F8F9FA) for section differentiation.

## Typography

This design system uses a dual-font strategy to balance character with utility.

- **Headlines (Montserrat):** A geometric sans-serif that feels bold and authoritative. It should be used for all primary headings to establish a clear hierarchy.
- **Body & Interface (Inter):** Chosen for its exceptional legibility at small sizes and its neutral, professional tone. All functional text, labels, and long-form content should use Inter.
- **Formatting:** Use tight letter spacing for large display titles to give them a modern, "designed" feel. Use increased letter spacing for labels to improve scannability.

## Layout & Spacing

The layout follows a **Fluid Grid** model with high-density internal spacing but low-density external margins to create a "breathable" experience.

- **Grid:** Use a 12-column grid for desktop and a 4-column grid for mobile.
- **Rhythm:** Spacing is built on an 8px base unit. Component padding should prioritize generous horizontal breathing room (e.g., 32px or 48px padding for cards) to reinforce the premium brand feel.
- **Mobile Adaption:** On mobile, margins reduce to 16px, and multi-column layouts should reflow into a single-column vertical stack, with the exception of small icon-grids (e.g., service chips) which may remain 2-column.

## Elevation & Depth

Visual hierarchy is established through **Tonal Layers** and **Ambient Shadows**. 

- **Surfaces:** Main page backgrounds are flat white. Secondary content areas or "cards" should use a very subtle, diffused shadow (0px 4px 20px rgba(0, 43, 73, 0.05)) to lift them slightly off the background without appearing heavy.
- **Depth:** Higher elevation is reserved for interactive elements like buttons and active input fields. 
- **Accents:** Use thin, low-opacity borders (1px solid #E5E7EB) for cards instead of heavy shadows to maintain the "clean" minimalist aesthetic.

## Shapes

The shape language is consistently **Rounded**, reflecting an approachable and modern firm.

- **Components:** Standard buttons and input fields utilize a 0.5rem (8px) radius.
- **Containers:** Larger cards and section wrappers should use a 1rem (16px) radius to create a soft, friendly containment for data and text.
- **Icons:** Icons should be enclosed in circular or highly rounded containers to match the logo’s organic feel.

## Components

### Buttons
- **Primary:** Soft Gold (#C5A059) background with Dark Blue (#002B49) text. This high-contrast pairing signals the most important action.
- **Secondary:** White background with a 2px Dark Blue border and text.
- **WhatsApp Action:** Bright Green (#25D366) background with White text and a specific "phone/chat" icon prefix. This button should often be "sticky" on mobile.

### Cards
Cards are the primary container for services. They should feature a white background, the 1rem corner radius, and a subtle icon at the top left. Hover states should include a slight vertical lift and a Soft Gold accent border on the left or bottom.

### Inputs
Text fields should use a light gray stroke and 8px corners. On focus, the border should transition to the Primary Deep Petrol color with a subtle outer glow.

### Lists & Chips
Service lists should use custom icons rather than standard bullets. Chips (for categories like "Tax" or "Audit") should use a desaturated version of the Primary color (e.g., a light blue tint) with dark text to maintain legibility.