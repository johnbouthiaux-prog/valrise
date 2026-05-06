# VALRISE — Website (v1)

Single-file premium one-pager. Built for fast deploy, easy editing, and full alignment with the VALRISE brand guidelines.

---

## Quick view

Open `index.html` directly in your browser to see the live site — no build step required.

---

## Brand alignment

The site is built strictly to your guideline document:

| Element | Spec | Used |
|---|---|---|
| Primary navy | `#1B2B3E` | hero, dark sections, footer |
| Secondary navy (logo on light) | `#2E3F53` | accents, body text on light |
| Pure white | `#FFFFFF` | logo on dark, form fields |
| Metallic gold (accent) | `#C9A961` | accents, italic emphasis, buttons |
| Ivory cream | `#F5F1EA` | section backgrounds (warm light) |
| Wordmark font | Cinzel (Trajan-style serif) | nav + footer brand |
| Headline font | Cormorant Garamond | all H1–H4 |
| Body font | Inter | sans body, eyebrows, buttons |

**Logo:** Currently rendered as a typographic wordmark (`VALRISE` in Cinzel). When you send me your final logo files (SVG preferred), I will swap them in. The CSS variables make this trivial.

---

## Sections (in order)

1. **Hero** — full-screen navy with atmospheric restaurant photography behind subtle gradients, headline & dual CTA
2. **Marquee** — scrolling band with the three pillars
3. **Aesthetic Universe** — 7-tile asymmetric image gallery showcasing concept, plating, service, atmosphere
4. **Manifesto** — the From → To statement (Idea/Confusion/Underperformance → Clarity/Structure/Profitability)
5. **The Valrise Model** — 3 strategic pillars
6. **Strategic Process** — 3-phase timeline
7. **Services** — image-led layout: each service has its own atmospheric photo, alternating left/right
8. **Engagement Model** — 3-step structure
9. **Method in Motion** — animated SVG performance trajectory chart with 4 phase markers + 3-pillar KPI row
10. **Investment** — diagnostic cards (Recommended highlight on Integrated), qualitative engagement tiers (no public engagement numbers), add-on modules with ranges
11. **Who We Partner With** — primary clients & typical challenges
12. **Founder** — chef-led credibility statement with atmospheric wine-cellar background, quote, stats
13. **Contact / Book a Call** — qualification call form
14. **Footer**

---

## To customize

### Swap logo
Replace the `.nav__brand` and `.footer__brand` text with an `<img src="logo.svg">` once you send the file.

### Change palette
All colors live as CSS variables at the top of the `<style>` block — search for `:root {` and edit the hex codes. Everything updates instantly.

### Connect the form
The form is currently front-end only and shows a success message on submit. Three quick options to make it live:

- **Calendly** — replace the form with a Calendly inline embed for the 20-min qualification call (fastest path, recommended)
- **Formspree** (free) — change `<form>` to `<form action="https://formspree.io/f/YOUR_ID" method="POST">` and you’re done
- **Backend** — uncomment the `fetch()` line in the script and point to your endpoint

### Update email / contact details
Search `contact@valrise.com` in the file and swap to the real address. Same for the “Dubai · GCC” line.

---

## Deploy (when ready)

The site is a single HTML file — drop it on any host:

- **Vercel / Netlify** — drag the `Website/` folder, get a live URL in 30 seconds
- **GitHub Pages** — push to a repo, enable Pages
- **Custom domain** (e.g. `valrise.com`) — point DNS to the host above

---

## Next iterations to consider

- Calendly integration for direct call booking (replaces form)
- Add a small **Insights** / journal section for thought leadership (positions you as Corporate / Cluster Director profile)
- Bilingual toggle (EN / FR) — for French investors and family offices in the GCC
- Case-study placeholder with anonymized engagement summaries (when you have permission)
- Subtle motion intro on logo / hero (Lottie or CSS) once final brand assets land

---

*Built May 2026 · Aligned to VALRISE Brand Foundation v2.0*
