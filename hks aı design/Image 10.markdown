---
name: Algorithmic Clarity
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
  on-surface-variant: '#434656'
  inverse-surface: '#283044'
  inverse-on-surface: '#eef0ff'
  outline: '#737688'
  outline-variant: '#c3c5d9'
  surface-tint: '#004ced'
  primary: '#003ec7'
  on-primary: '#ffffff'
  primary-container: '#0052ff'
  on-primary-container: '#dfe3ff'
  inverse-primary: '#b7c4ff'
  secondary: '#506600'
  on-secondary: '#ffffff'
  secondary-container: '#c1f100'
  on-secondary-container: '#546b00'
  tertiary: '#4b4e50'
  on-tertiary: '#ffffff'
  tertiary-container: '#636668'
  on-tertiary-container: '#e2e4e6'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dde1ff'
  primary-fixed-dim: '#b7c4ff'
  on-primary-fixed: '#001452'
  on-primary-fixed-variant: '#0038b6'
  secondary-fixed: '#c3f400'
  secondary-fixed-dim: '#abd600'
  on-secondary-fixed: '#161e00'
  on-secondary-fixed-variant: '#3c4d00'
  tertiary-fixed: '#e0e3e5'
  tertiary-fixed-dim: '#c4c7c9'
  on-tertiary-fixed: '#191c1e'
  on-tertiary-fixed-variant: '#444749'
  background: '#faf8ff'
  on-background: '#131b2e'
  surface-variant: '#dae2fd'
typography:
  display-lg:
    fontFamily: Hanken Grotesk
    fontSize: 72px
    fontWeight: '800'
    lineHeight: '1.1'
    letterSpacing: -0.04em
  display-lg-mobile:
    fontFamily: Hanken Grotesk
    fontSize: 40px
    fontWeight: '800'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Hanken Grotesk
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
    letterSpacing: -0.02em
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: '0'
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: '0'
  label-caps:
    fontFamily: Geist
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: 0.1em
  mono-data:
    fontFamily: Geist
    fontSize: 14px
    fontWeight: '400'
    lineHeight: '1.4'
    letterSpacing: '0'
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1280px
  gutter: 24px
  margin-mobile: 20px
  section-gap-lg: 160px
  element-gap-md: 32px
---

## Brand & Style
The design system embodies a fusion of mathematical precision and digital fluidness. It targets high-growth startups and tech-forward enterprises seeking a bridge between complex AI engineering and intuitive user experience. 

The aesthetic is **Modern Minimalist with Glassmorphic accents**. It prioritizes extreme legibility and "breathable" layouts. By leveraging large whitespace and structural geometric patterns, the UI reflects the founder's background in Math and Computer Science—projecting an image of intellectual rigor and innovative clarity. The interface should feel like a high-end laboratory: sterile but inviting, complex but ordered.

## Colors
The palette is rooted in a "High-Definition Light" scheme. 

- **Primary (Electric Blue):** Used for primary actions, active states, and highlighting key mathematical insights.
- **Secondary (Cyber Lime):** Reserved for "AI-active" elements, success states, and high-energy accents. It should be used sparingly to maintain professionalism.
- **Tertiary (Frost White):** The foundation of the glassmorphic layers and background sections.
- **Neutral (Deep Slate):** Used strictly for typography and structural borders to ensure high contrast against the light backgrounds.

Avoid pure black; use the Deep Slate neutral to maintain a softer, more modern tech feel.

## Typography
The typography strategy uses **Hanken Grotesk** for a sharp, contemporary display feel and **Inter** for bulletproof legibility in body copy. **Geist** is introduced for labels and technical data, nodding to the developer-centric nature of the agency.

- Use **display-lg** for hero sections with tight letter spacing.
- Use **mono-data** for technical specs, AI model parameters, or mathematical annotations.
- Maintain generous paragraph spacing (1.6x) to support the "airy" brand requirement.

## Layout & Spacing
The layout follows a **Strict 12-Column Grid** with a logic-based spacing system. 

- **Grid:** Use a fluid container with a max-width of 1280px. Gutters are fixed at 24px to ensure breathing room between columns.
- **Sectioning:** Vertical rhythm is driven by large gaps (160px+) to separate distinct service offerings or case studies, reinforcing the "Fresh" aesthetic.
- **Mathematical Alignment:** Elements should be aligned to the grid with mathematical precision. Avoid centered layouts for technical content; use asymmetrical left-aligned compositions to create dynamic visual interest.

## Elevation & Depth
Depth is achieved through **Glassmorphism and Tonal Stacking** rather than traditional heavy shadows.

- **Surface Layer:** The base is a soft gray (#F1F5F9).
- **Glass Layer:** Floating cards use a white semi-transparent fill (80% opacity) with a `backdrop-filter: blur(12px)`.
- **Borders:** Instead of shadows, use "Ghost Borders"—1px solid lines with low opacity (10% Neutral) to define shapes.
- **Shadows:** When necessary for interactivity, use highly diffused, low-opacity blue-tinted shadows (e.g., `rgba(0, 82, 255, 0.08)`) to suggest a soft glow rather than a physical weight.

## Shapes
The shape language is **Refined and Geometric**. 

- **Corners:** Use the `rounded` (0.5rem) setting for standard components and `rounded-lg` (1rem) for large cards. This strikes a balance between professional rigor (sharpness) and modern friendliness (softness).
- **Geometric Accents:** Incorporate subtle background patterns of SVG dot-grids or thin-line geometric proofs (triangulations, Voronoi patterns) at 5% opacity to reinforce the Computer Science narrative.

## Components
- **Buttons:** Primary buttons are Electric Blue with white text. Hover states should utilize a subtle vertical lift and an increase in shadow diffusion. Use "Cyber Lime" only for "Live Demo" or "AI Launch" specific actions.
- **Glass Cards:** Used for service features. They must include a 1px inner light border to simulate the edge of a glass pane.
- **Input Fields:** Minimalist design with only a bottom border that transitions to Electric Blue on focus. Use Geist for placeholder text to maintain the technical aesthetic.
- **AI Indicator Chips:** Small, pill-shaped badges using a Cyber Lime background with dark slate text to highlight "AI-Powered" features.
- **Code Snippets:** For demonstrating custom scripts, use a frost-white container with Geist Mono text, maintaining the light theme (no dark code blocks).