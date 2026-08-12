# Soma Tanaka — Digital Marketer Portfolio

A static portfolio site for Soma Tanaka, a Digital Marketer with 6+ years of experience in full-funnel marketing, lead generation, and paid advertising.

---

## ✅ Completed Features

### Design (v3 — White/Light Theme)
- **White/light base** with pale lavender tint sections (`#f7f6ff`)
- **Purple accent** (`#7c3aed`) throughout — buttons, tags, gradients, ticker
- **Flat card style** — subtle shadows, clean borders, no glow effects
- **Purple ticker stripe** between hero and about sections (scrolling marquee)
- **Dark footer/contact** section as contrast (`#18162a`)
- Space Grotesk (headings) + Inter (body) fonts

### Pages
- `index.html` — Full portfolio homepage
- `works/index.html` — All works listing (6 projects)
- `works/satellite-office.html` — Satellite Office LP detail
- `works/realestate-foreign.html` — Real Estate (Foreign Customers) LP detail
- `works/realestate-fukuoka.html` — Fukuoka Real Estate LP detail
- `works/lowcost-brokerage.html` — Low-Cost Brokerage LP detail
- `works/sendai-realestate.html` — Sendai RE LP (private case study)
- `works/hokkaido-realestate.html` — Hokkaido RE LP (private case study)

### Sections (index.html)
1. **Hero** — Left-aligned, profile photo right, stats row, CTA buttons
2. **Ticker Stripe** — Purple scrolling marquee of skills/tools
3. **About** — 2-col grid with KPI card
4. **Experience Timeline** — 3 roles (DEA, Renobank, Mental Health Lab)
5. **Works** — 4 cards with real screenshots, KPI rows, click-through to detail
6. **Unpublicly Shareable Case Works** — 2 private cases with insight callouts
7. **Tools** — 4 categories incl. AI Tools (ChatGPT, Claude, NotebookLM, Gemini, Genspark)
8. **Skills** — Pill grid of competencies
9. **Contact** — Dark section with email + LinkedIn
10. **Footer** — Dark, clean

### Interactions
- Scroll reveal (IntersectionObserver, staggered)
- Active nav highlight while scrolling
- Work cards clickable → detail pages
- Number counter animation on KPIs
- Mobile hamburger menu
- Smooth scroll for anchor links

---

## 🗂 File Structure

```
index.html
css/
  style.css          ← v3: white/light base + purple accent
js/
  main.js            ← scroll reveal, hamburger, nav highlight, counter
images/
  work-satellite.jpg
  work-realestate-foreign.jpg
  work-realestate-fukuoka.jpg
  work-lowcost-lp.jpg
works/
  index.html
  satellite-office.html
  realestate-foreign.html
  realestate-fukuoka.html
  lowcost-brokerage.html
  sendai-realestate.html
  hokkaido-realestate.html
```

---

## 🔧 CSS Design Tokens (v3)

```css
--bg:          #ffffff
--bg-off:      #f7f6ff    /* pale lavender sections */
--bg-card:     #f4f3fc
--bg-dark:     #18162a    /* footer / contact */
--purple:      #7c3aed
--shadow-sm:   0 2px 12px rgba(100,80,200,0.08)
--shadow-md:   0 6px 28px rgba(100,80,200,0.12)
```

---

## ⚠️ Pending (User Action Required)

- Replace `href="#"` Figma link placeholders in all detail pages with real Figma URLs
- Replace `mailto:soma@example.com` with real email
- Replace `https://linkedin.com` with real LinkedIn profile URL
- Add profile photo — currently using Genspark API URL (may expire)

---

## 🚀 Deployment

GitHub Pages compatible — no build step required. Push to `gh-pages` branch or deploy root directory.

To deploy: use the **Publish tab** to make the site live instantly.
