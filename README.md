<div align="center">

<br/>

<img src="https://mambapointhotel.com/wp-content/uploads/2019/11/Mambapointhotel_03.png" alt="Mamba Point Hotel" width="220"/>

<br/><br/>

# MAMBA POINT HOTEL
### *Monrovia, Liberia — Luxury Demo Website*

<br/>

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![No Framework](https://img.shields.io/badge/No_Framework-Pure_Vanilla-C9A84C?style=flat-square)
![License](https://img.shields.io/badge/License-Demo-C9A84C?style=flat-square)

<br/>

> *"Liberia's most distinguished address — overlooking the Atlantic Ocean in Monrovia's Diplomatic Quarter."*

<br/>

---

</div>

## ✦ Overview

A fully custom, luxury hotel demo website built for **Mamba Point Hotel** — a cinematic, dark-themed single-page experience designed to convert visitors into guests. Zero dependencies. Zero frameworks. Pure HTML, CSS & JavaScript.

Built as a high-end demo to showcase what a modern luxury hospitality website should feel and look like.

<br/>

## ✦ Features

### Visual & Animation
- **Film grain overlay** — animated SVG turbulence texture for a cinematic feel
- **Ken Burns hero** — slow-zoom parallax background with particle constellation canvas
- **3D card tilt** — mousemove-driven `perspective` rotation on room & booking cards
- **Gold particle burst** — canvas physics explosion on every CTA click
- **Floating 3D shapes** — CSS `preserve-3d` gold diamond accents in the hero
- **SVG wave separators** — smooth transitions between sections
- **Scroll-reveal animations** — `IntersectionObserver`-powered fade-ins

### Sections
| Section | Description |
|---|---|
| **Navigation** | Fixed glassmorphism nav with scroll-aware opacity |
| **Hero** | Full-viewport cinematic with particle canvas + booking CTA |
| **Quick Booking Bar** | Sticky date/room selector |
| **About** | Story, stats (animated counters), and heritage |
| **Rooms** | 3 room tiers with 3D tilt cards + modal booking |
| **Book Direct** | Airbnb-style direct booking with live pricing calculator |
| **Dining** | Horizontal cinema reel — 4 venues with scroll-snap |
| **Amenities** | Icon grid with hover reveal |
| **Location** | Dark-themed Google Maps embed |
| **Contact** | WhatsApp integration + contact form |
| **Footer** | Full luxury footer with social links |

### Booking System
- **Modal booking form** — name, email, phone, check-in/out, room type, special requests
- **Book Direct calculator** — live price updates based on date selection (nights × rate)
- **WhatsApp CTA** — direct deep-link to hotel's WhatsApp number
- **Success state** — animated confirmation after form submission

<br/>

## ✦ Tech Stack

```
HTML5       → Single index.html, fully self-contained
CSS3        → Custom properties, Grid, Flexbox, scroll-snap, 3D transforms
JavaScript  → Vanilla ES6+, Canvas 2D API, IntersectionObserver, RAF
Fonts       → Cormorant Garamond (headings) + Montserrat (body) via Google Fonts
Images      → Hotlinked from mambapointhotel.com
Maps        → Google Maps embed (no API key required)
```

<br/>

## ✦ Design System

```css
--gold:         #C9A84C   /* Primary accent */
--gold-light:   #E8C96B   /* Hover state */
--dark:         #0A0A08   /* Page background */
--dark2:        #0F0F0C   /* Card backgrounds */
--dark3:        #161613   /* Section backgrounds */
--cream:        #F5F0E8   /* Heading text */
--text:         #B8AE9C   /* Body text */

Font Headings:  Cormorant Garamond (300–600, italic)
Font Body:      Montserrat (200–700)
```

<br/>

## ✦ Getting Started

No build step. No installs. Just open the file.

```bash
git clone https://github.com/sameermotwani17-cell/mamba-point-hotel.git
cd mamba-point-hotel

# Open directly in browser
open index.html          # macOS
start index.html         # Windows
xdg-open index.html      # Linux
```

Or serve locally:
```bash
npx serve .
# → http://localhost:3000
```

<br/>

## ✦ Project Structure

```
mamba-point-hotel/
└── index.html          # Everything — styles, markup, scripts, all in one file
```

<br/>

## ✦ Live Preview

> Deploy to Vercel, Netlify, or GitHub Pages — just point to `index.html`.

```bash
# GitHub Pages (one command)
gh-pages -d .

# Vercel
vercel deploy
```

<br/>

---

<div align="center">

<br/>

*Designed & developed as a luxury hospitality demo.*
*All hotel content, images, and branding belong to Mamba Point Hotel, Monrovia, Liberia.*

<br/>

**[mambapointhotel.com](https://mambapointhotel.com)** &nbsp;·&nbsp; Monrovia, Liberia &nbsp;·&nbsp; Est. 1993

<br/>

</div>
