<div align="center">

# T A S I B U L &nbsp; H A S A N

### Humanities Student · Writer · Observer

*Words, solitude and fleeting light — from Bangladesh.*

<br>

![HTML5](https://img.shields.io/badge/HTML5-021a19?style=for-the-badge&logo=html5&logoColor=2bb3a6)
![CSS3](https://img.shields.io/badge/CSS3-06302d?style=for-the-badge&logo=css3&logoColor=9fd1ca)
![JavaScript](https://img.shields.io/badge/Vanilla_JS-021a19?style=for-the-badge&logo=javascript&logoColor=2bb3a6)
![Zero Dependencies](https://img.shields.io/badge/Dependencies-0-2bb3a6?style=for-the-badge)

[**Live Site**](https://tsblhsn.github.io) &nbsp;·&nbsp; [**Instagram**](https://www.instagram.com/tsblhsn/) &nbsp;·&nbsp; [**X / Twitter**](https://x.com/tsblhsn)

</div>

---

## ✦ Overview

A personal portfolio built as **one hand-written HTML file**. No frameworks, no build step, no bundlers. Just clean markup, modern CSS and a little vanilla JavaScript, wrapped in a deep-sea aurora aesthetic.

The site introduces who I am, showcases **Metasoco** (my creative venture), shares original philosophical observations, and closes with a swipeable photography archive.

---

## ✦ Sections

| Section | What it holds |
| :-- | :-- |
| **Hero** | Animated name reveal, portrait with unveil effect, rotating text badge, social links |
| **About** | The story so far: writing, solitude, photography, and the bigger dream |
| **Metasoco** | An evolving ecosystem of creative and conceptual ventures, with a live marquee |
| **Philosophical Thoughts** | Original social observations in an editorial, two-column layout |
| **Visual Archives** | A drag-and-swipe photography gallery with snap scrolling |
| **Contact** | One clean call-to-action to start a conversation |

---

## ✦ Design Language

**Theme:** *Abyss & Aurora* — deep teal darkness, soft drifting light.

| Token | Hex | Role |
| :-- | :-- | :-- |
| `--abyss` | `#021a19` | Page background |
| `--deep` | `#06302d` | Alternating bands |
| `--teal` | `#2bb3a6` | Accent, highlights |
| `--mist` | `#9fd1ca` | Body text |
| `--foam` | `#e4f6f2` | Headings |

**Typography**

- **Playfair Display** — editorial serif for headings and quotes
- **Manrope** — clean, modern sans for body text

---

## ✦ Highlights

- **Letter-by-letter title animation** — each character rises into place
- **Aurora background** — two blurred, slowly drifting light orbs
- **Portrait unveil** — clip-path reveal with an offset outline frame
- **Rotating circular text badge** — pure SVG `textPath`
- **Infinite marquee** — pauses on hover
- **Scroll-reveal sections** — powered by `IntersectionObserver`
- **Drag-to-scroll gallery** — mouse drag on desktop, native swipe on mobile
- **Sticky blurred navigation** — scrolls horizontally on small screens
- **Fully responsive** — mobile-first, fluid type with `clamp()`
- **Accessible** — focus outlines, alt text, `aria` labels and `prefers-reduced-motion` support

---

## ✦ Project Structure

```
.
├── index.html           # The entire site: markup, styles, scripts
├── IMG_5585_Original.jpeg   # Hero portrait
├── IMG_0999.jpeg … IMG_1026.jpeg   # Gallery photographs
└── README.md
```

---

## ✦ Run Locally

No installation needed.

```bash
# 1. Clone the repository
git clone https://github.com/tsblhsn/tsblhsn.github.io.git
cd tsblhsn.github.io

# 2. Open it
open index.html          # macOS
start index.html         # Windows
xdg-open index.html      # Linux
```

Or serve it with any static server:

```bash
npx serve .
# or
python3 -m http.server 8000
```

---

## ✦ Customize

**Add or remove gallery photos** — edit the `ids` array near the bottom of `index.html`:

```js
var ids = ["0999", "1001", "1002" /* … */];
```

Each ID maps to a file named `IMG_<id>.jpeg` in the project root.

**Change the Metasoco marquee words** — edit the `words` array:

```js
var words = ["Creative Writing", "Media Production" /* … */];
```

**Re-theme the site** — change the CSS variables at the top of the `<style>` block:

```css
:root {
  --abyss: #021a19;
  --teal:  #2bb3a6;
  /* … */
}
```

---

## ✦ Deploy

This repository is a GitHub user site, so it is served automatically at **https://tsblhsn.github.io** once `index.html` is on the default branch (Settings → Pages → select branch → Save, if it isn't enabled yet).

Because it is a static site, it also deploys anywhere in seconds:

- **GitHub Pages** — Settings → Pages → select branch → Save
- **Netlify** — drag and drop the project folder
- **Vercel** — import the repository, no config needed
- **Cloudflare Pages** — connect the repo, leave the build command empty

---

## ✦ Browser Support

Built for modern evergreen browsers (Chrome, Edge, Firefox, Safari). Uses `clip-path`, `backdrop-filter`, `svh` units and `IntersectionObserver`.

---

## ✦ Connect

<div align="center">

**Let's share some thoughts.**

[Instagram](https://www.instagram.com/tsblhsn/) &nbsp;·&nbsp; [X / Twitter](https://x.com/tsblhsn)

<br>

<sub>© 2026 Tasibul Hasan · @tsblhsn</sub>

</div>
