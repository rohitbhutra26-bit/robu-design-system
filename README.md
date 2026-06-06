# ROBU Design System

A warm, editorial design language for Indian financial apps.
Cream surfaces · Terracotta accent · Serif headings · Spring motion.

## Files

| File | Purpose |
|---|---|
| `robu-tokens.css` | CSS custom properties (framework-agnostic) |
| `tailwind.robu.js` | Tailwind `theme.extend` config snippet |
| `robu-design-system.html` | Visual design documentation |

## Quick start

```css
/* globals.css */
@import './robu-tokens.css';
```

```js
// tailwind.config.js
const robu = require('./tailwind.robu.js');
module.exports = { theme: { extend: robu } };
```

Toggle themes:
```js
document.documentElement.setAttribute('data-theme', 'dark');
document.documentElement.setAttribute('data-theme', 'light');
```

## Fonts (add to your <head>)
```html
<link href="https://fonts.googleapis.com/css2?family=DM+Sans:wght@300;400;500;600;700&family=Lora:ital,wght@0,400;0,600;0,700;1,400&family=IBM+Plex+Mono:wght@400;500;600&display=swap" rel="stylesheet">
```
