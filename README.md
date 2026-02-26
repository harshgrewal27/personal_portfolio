# Harsh Grewal — Personal Portfolio Website

A dark-themed, responsive personal portfolio website for **Harsh Grewal**, a Data Engineer specializing in Azure, Databricks, and cloud-native data pipelines.

---

## Live Preview

Open `harsh-grewal-portfolio.html` directly in any modern browser — no build step or server required.

---

## Features

- **Fully Responsive** — optimized for mobile, tablet, and desktop
- **Single HTML File** — zero dependencies, no frameworks, no build tools
- **Smooth Animations** — scroll-triggered reveal effects and staggered transitions
- **Mobile Navigation** — hamburger menu with full-screen overlay
- **Active Nav Highlighting** — nav links highlight as you scroll through sections
- **Google Fonts** — uses Syne, DM Mono, and DM Sans (loaded via CDN)

---

## Sections

| Section | Description |
|---|---|
| **Hero** | Name, role, summary, key stats, and CTA buttons |
| **Experience** | Timeline of professional experience at Capgemini |
| **Skills** | Categorized technical skills with hover-interactive tags |
| **Certifications** | Microsoft AZ-900, Databricks Associate & Professional |
| **Achievements** | Awards and competitive exam results |
| **Education** | Academic history with CGPA/percentage |
| **Contact** | Email, phone, and LinkedIn links |

---

## Tech Stack

- **HTML5** — semantic structure
- **CSS3** — custom properties, grid, flexbox, keyframe animations, `IntersectionObserver`-driven reveals
- **Vanilla JavaScript** — scroll spy, mobile menu toggle, staggered animation delays
- **Google Fonts CDN** — Syne (headings), DM Mono (labels/code), DM Sans (body)

No npm. No bundler. No framework. Just open the file.

---

## Design System

### Color Palette

| Token | Value | Usage |
|---|---|---|
| `--bg` | `#050810` | Page background |
| `--surface` | `#0d1117` | Card backgrounds |
| `--surface2` | `#161b27` | Subtle elevated surfaces |
| `--accent` | `#00d4ff` | Primary accent (cyan) |
| `--accent2` | `#7b61ff` | Secondary accent (purple) |
| `--accent3` | `#00ff94` | Highlight / success (green) |
| `--text` | `#e8eaf0` | Primary text |
| `--muted` | `#6b7280` | Secondary / subdued text |

### Typography

- **Display / Headings** — `Syne` (800 weight) — bold, geometric, editorial
- **Monospace / Labels** — `DM Mono` — used for tags, badges, and nav links
- **Body** — `DM Sans` — clean and readable for descriptions

---

## File Structure

```
portfolio/
└── harsh-grewal-portfolio.html   # Complete portfolio (self-contained)
└── README.md                     # This file
```

---

## Customization

### Update Personal Info
All content is in the HTML body. Search for the relevant section comment (e.g., `<!-- HERO -->`, `<!-- EXPERIENCE -->`) and edit the text directly.

### Change Colors
Update CSS custom properties at the top of the `<style>` block:

```css
:root {
  --accent: #00d4ff;   /* Change primary accent color */
  --accent2: #7b61ff;  /* Change secondary accent color */
}
```

### Add a New Section
1. Add a `<section id="your-section">` block in the HTML body
2. Add a nav link `<a href="#your-section">Label</a>` in the `<ul class="nav-links">` and mobile menu
3. Add a corresponding mobile menu link

### Add Profile Photo
In the hero section, replace the stats cards with an `<img>` tag or add it alongside:

```html
<img src="your-photo.jpg" alt="Harsh Grewal"
  style="width:200px;height:200px;border-radius:50%;border:2px solid var(--accent);" />
```

---

## Browser Support

Works in all modern browsers — Chrome, Firefox, Safari, and Edge. Requires JavaScript enabled for scroll animations and mobile menu.

---

## Contact

**Harsh Grewal**
- Email: harshgrewal2700@gmail.com
- Phone: +91 72908 00101
- LinkedIn: [linkedin.com/in/harshgrewal](https://linkedin.com/in/harshgrewal)
