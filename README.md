# Website Template 7

Responsive multi-page HTML/CSS website template #7 in the LadeStack template series. Built with Bootstrap, custom CSS, and FontAwesome icon fonts — zero build step required.

## ✨ Features

- 5 ready-to-customize pages: Home, About, Services, Portfolio, Contact
- Bootstrap-grid layout for responsive behaviour on mobile, tablet, and desktop
- Modular CSS split: `default.css` (theme) + `custom.css` (overrides) + `combined.min.css` (production)
- Icon set: full FontAwesome webfont (`.eot`, `.svg`, `.ttf`, `.woff`) + `.otf`
- `bootstrap.min.js` for off-the-shelf interactive components
- SEO-friendly `sitemap.xml` included
- Drop-in `http-server` setup — no build pipeline needed

Distinct "Portfolio" page to highlight case studies or featured projects alongside services.

## 📄 Pages included

- **Home**
- **About**
- **Services**
- **Portfolio**
- **Contact**

## 🛠️ Tech stack

- HTML5
- CSS3 (`default.css`, `custom.css`, `combined.min.css`)
- Bootstrap 3 grid + `bootstrap.min.js`
- FontAwesome icon webfont
- Node.js `http-server` for local serving

## 🚀 Getting started

```bash
# Option 1 — http-server (matches the repo's package.json)
npm install
npm start    # serves on http://localhost:8080

# Option 2 — any static server
python -m http.server 8080
```

Then open <http://localhost:8080/home.html> (or `index.html` once you set it as the entry).

## 📁 Project structure

```
.
├── home.html
├── about-us.html / about.html
├── contact-us.html / contact.html
├── services.html
├── our-gallery.html / gallery.html
├── css/
│   ├── default.css
│   ├── custom.css
│   └── combined.min.css
├── js/
│   └── bootstrap.min.js
├── fonts/                # FontAwesome webfont + .otf
├── sitemap.xml
└── package.json
```

## 🎨 Customization

1. Replace placeholder text inside each HTML file directly.
2. Tweak theme colours in `css/default.css` — variables are at the top.
3. Add per-section overrides in `css/custom.css`.
4. Drop new icons in by referencing them from `fonts/FontAwesome.otf`.

## 📜 License

Released for personal and commercial use. Attribution appreciated but not required.

---

> Part of the **Website-template** series — explore templates 1–7 for layout alternatives.

---

Built by [Girish Lade](https://github.com/girishlade111) · [ladestack.in](https://ladestack.in)
