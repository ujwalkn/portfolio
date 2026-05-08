# Ujwal K N — Personal Portfolio

> A clean, modern personal portfolio website built with vanilla HTML, CSS, and JavaScript. No frameworks, no build tools — just one file, ready to deploy.

🔗 **Live site:** [ujwalkn.github.io/portfolio](https://ujwalkn.github.io/portfolio)

---

## 📌 Overview

This portfolio showcases my work, skills, and experience as a Full-Stack Software Engineer with 3 years of professional experience in `.NET`, `React`, and `SQL`.

**Highlights:**
- Fully responsive — works on mobile, tablet, and desktop
- Smooth scroll-triggered animations via Intersection Observer
- No dependencies, no build step — a single `index.html` file
- Hosted for free on GitHub Pages

---

## 🛠 Tech Stack

| Layer | Technology |
|---|---|
| Markup | HTML5 |
| Styling | CSS3 (custom properties, grid, flexbox, animations) |
| Scripting | Vanilla JavaScript (ES6+) |
| Fonts | [Syne](https://fonts.google.com/specimen/Syne) + [DM Sans](https://fonts.google.com/specimen/DM+Sans) via Google Fonts |
| Hosting | GitHub Pages |

---

## 🚀 Running Locally

No installs or build tools required.

**Option 1 — Open directly**
```bash
# Clone the repo
git clone https://github.com/ujwalkn/portfolio.git
cd portfolio

# Open in your browser
open index.html          # macOS
start index.html         # Windows
xdg-open index.html      # Linux
```

**Option 2 — Use a local server (recommended for accurate rendering)**
```bash
# With Python
python3 -m http.server 8000
# Then visit http://localhost:8000

# Or with VS Code — install the "Live Server" extension
# Right-click index.html → Open with Live Server
```

---

## 🎨 Customizing

All content and styles live in `index.html`. Here's what to change:

### Personal Info
Search for these fields and update them:
```
"Ujwal K N"           → Your name
"ujwalkn2000@gmail.com" → Your email
"8296462725"          → Your phone
"Bangalore, India"    → Your location
"Vela Technologies"   → Your company
```

### Colors
The entire color scheme is controlled by CSS variables at the top of the `<style>` block:
```css
:root {
  --bg: #080b0f;          /* Page background */
  --accent: #e8a140;      /* Primary accent (amber) */
  --accent2: #2dd4bf;     /* Secondary accent (teal) */
  --text: #e6edf3;        /* Body text */
  --muted: #6e7a87;       /* Muted/secondary text */
}
```

### Sections
The portfolio has four main sections — each clearly commented in the HTML:
- `<!-- HERO -->` — Name, title, intro, CTA buttons
- `<!-- ABOUT -->` — Bio and contact details
- `<!-- SKILLS -->` — Skill category cards
- `<!-- EXPERIENCE -->` — Work timeline
- `<!-- EDUCATION -->` — Education cards

### Adding a Custom Domain
1. Buy a domain (recommended: [Namecheap](https://namecheap.com) or [Cloudflare](https://cloudflare.com/products/registrar))
2. Add a `CNAME` file to this repo root containing just your domain:
   ```
   yourdomain.dev
   ```
3. Add these DNS `A` records at your registrar:
   ```
   185.199.108.153
   185.199.109.153
   185.199.110.153
   185.199.111.153
   ```
4. Add a `CNAME` record: `www` → `ujwalkn.github.io`
5. In GitHub: **Settings → Pages → Custom domain** → enter your domain → enable **Enforce HTTPS**

---

## 📄 License

This project is open source under the [MIT License](LICENSE).

Feel free to fork and adapt it for your own portfolio — a credit or star is appreciated but not required. 🙂

---

<p align="center">Built by <strong>Ujwal K N</strong> · <a href="mailto:ujwalkn2000@gmail.com">ujwalkn2000@gmail.com</a></p>
