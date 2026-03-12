# CV Luigy Roso — Project Notes

> Futuristic Apple-inspired HTML one-pager CV. Single file, zero dependencies. Resume point for all sessions.

---

## 1. Decisions

### Design
- **Light theme** — white bg (`#fbfbfd`), dark text (`#1d1d1f`), Apple-inspired
- **Frosted glass nav** — `backdrop-filter: blur(20px)` sticky nav
- **Gradient accents** — blue (`#0071e3`) to purple (`#a259ff`) used across headings, timeline nodes, stat numbers
- **Scroll-reveal animations** — elements fade up with `IntersectionObserver`, 0.8s cubic-bezier transitions
- **Metrics pop-in** — staggered cascade animation (0.15s delay per badge), scale + fade, hover effect
- **Pill-shaped buttons/links** — `border-radius: 980px` Apple style
- **Responsive** — grid collapses on mobile, adjusted spacing

### Architecture
- **Single HTML file** — all CSS and JS inline, no external dependencies
- **Profile photo** — `profile.png` in project root
- **Project screenshots** — captured via Puppeteer from live GitHub Pages (`preview-fitness.png`, `preview-flipfinder.png`)
- **Puppeteer installed locally** for screenshots but excluded from git (package.json, node_modules in .gitignore)

### Content & Positioning
- **Title**: AI-Native Senior Product Manager
- **Tagline**: Growth & Revenue Optimization | B2C Platforms | Data-Driven Execution
- **Key stats in hero area**: 7+ years, 170K+ users, 100% freelance success
- **Removed**: The Flying Cock (Brisbane) — user decided not to include it
- **Timeline order**: Chronological (oldest first), from Jigger (2018) to Shifter (2025)
- **Each timeline entry has metric badges** — large number on top, label below, animated pop-in

### Sections (in order)
1. **Hero** — name, tagline, 2 CTAs
2. **About** — photo, summary, 3 stat counters
3. **Journey** — 9 timeline entries with metric badges
4. **Skills** — 7 cards (Product, Data, UX/UI, Tools, AI-Native, B2B/B2C, Leadership)
5. **Side Projects** — 2 project cards with screenshots (Tu Entrenamiento, Flip Finder)
6. **Education** — 4 cards (Master's Spain, Bachelor's Colombia, QUT Australia, Certifications)
7. **Contact** — email, LinkedIn, Calendly, phone
8. **Footer**

### Contact Info
- Email: luigy.roso@gmail.com
- LinkedIn: linkedin.com/in/luigyrosoproductmanagement
- Calendly: calendly.com/luigyroso/30min
- Phone: (+57) 304-675-4722

### Git & Deployment
- **Repo**: https://github.com/luigyroso/CV-Luigy-Roso (private)
- **Branch**: main
- **GitHub Pages**: enabled

---

## 2. Key Insights

- User's LinkedIn profile has significantly more detail than the CV PDF — always cross-reference both
- Zuppils has zero web presence (domains dead, no social media)
- Double Nines = 99s, digital product studio (Miami/Boulder/Medellin), Freepour is Bacardi & Diageo bartender education platform
- Pappcorn = Startup Studio in Bogota (600+ projects, 94% client recurrence)
- Newell Brands = global consumer goods (Rubbermaid, Sharpie, Coleman, Yankee Candle)
- Shifter.com.co is a new mobility marketplace — Luigy is founding/sole PM (0→1)

---

## 3. Tasks Done

1. Created project folder and initialized git repo
2. Built initial dark-theme draft HTML
3. Added .gitignore and README, pushed to GitHub
4. Switched to light theme (Apple-inspired)
5. Added profile photo to About section
6. Populated all CV content from first PDF (8 timeline entries, skills, education, contact)
7. Researched companies (Double Nines, Pappcorn, Newell Brands, Zuppils) via web
8. Enriched timeline descriptions with company context
9. Full overhaul with LinkedIn profile data — added Shifter, updated all numbers (170K users, engagement 55→83%, etc.)
10. Added key metrics/numbers to every experience
11. Removed The Flying Cock entry
12. Upgraded metrics UI — large numbers, staggered pop-in animation, hover effects
13. Added Side Projects section with Puppeteer screenshots (Tu Entrenamiento, Flip Finder)
14. Committed and pushed all changes

---

## 4. Tasks Pending

- Populate with any additional info Luigy provides
- Consider adding dark mode toggle
- Potential: add OG meta tags for social sharing
- Potential: deploy to custom domain
- Potential: add more side projects as they're created
