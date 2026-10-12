# Colour Theme Generator

A lightweight, zero-dependency colour palette and theme generator built with semantic HTML, modern vanilla CSS, and pragmatic JavaScript. Generate accessible theme pairings and export ready-to-use CSS custom properties for your design token system.

[Live Demo](https://trudymessingham.co.uk/playground/colour-theme-generato/) • [Tutorials & Guides](https://trudymessingham.co.uk/tutorials/) • [Bug Reports](https://github.com/tielmess/ideas-colour-theme-generator/issues)

---

## Overview

Most web theme generators rely on heavy front-end frameworks or spit out arbitrary hex codes without considering how design tokens work in production.

This project explores an evergreen front-end approach:

- **Zero build steps:** Runs directly in any modern browser using pure HTML, CSS, and vanilla JS.
- **Token-first mindset:** Generates structured CSS custom properties ready to drop straight into your `:root` stylesheet.
- **Accessible foundations:** Built using semantic markup, keyboard-friendly controls, and high-contrast fallbacks.

---

## Features

- **Instant Palette Generation:** Quickly explore complementary, harmonious colour combinations for web layouts.
- **CSS Token Export:** One-click copying of structured CSS custom property blocks for light and dark contexts.
- **Pure Vanilla Stack:** No React, no Tailwind, no bundlers—100% standard web technologies.
- **Accessible Controls:** Form inputs, labels, and interactive states aligned with WCAG AA standards.
- **Lightweight Footprint:** Sub-millisecond execution and negligible page weight.

---

## Token Output Example

The generator structures colours into semantic variables rather than raw values, making theme management clean and maintainable:

```css
:root {
  /* Brand Tokens */
  --color-primary: #1d4ed8;
  --color-primary-hover: #1e40af;
  --color-secondary: #0f766e;

  /* Surface & Background */
  --color-surface-base: #f8fafc;
  --color-surface-card: #ffffff;

  /* Text & Contrast */
  --color-text-main: #0f172a;
  --color-text-muted: #475569;

  /* Functional */
  --color-border: #e2e8f0;
}
```
