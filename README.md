# 🧑‍💻 Sattu Nithin — Personal Portfolio Website

> A fully responsive, single-page personal portfolio built with pure HTML, CSS, and JavaScript — inspired by the [Picto Figma template](https://www.figma.com/community/file/1170206889562959306/picto-personal-portfolio-free-template-community).

---

## 🔗 Live Demo

> Deploy this on GitHub Pages, Netlify, or Vercel — see [Deployment](#-deployment) below.

---

## 📸 Preview

![Portfolio Preview](https://img.shields.io/badge/Status-Live-brightgreen?style=flat-square)
![HTML](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

---

## 📁 Project Structure

```
portfolio/
│
├── index.html        # Main portfolio file (all-in-one: HTML + CSS + JS)
└── README.md         # You're reading it
```

> Everything lives in a single `index.html` file — no build tools, no dependencies, no frameworks. Just open it in a browser and it works.

---

## ✨ Features

- **Single-page layout** with smooth scroll navigation
- **Sticky navbar** with backdrop blur and active link highlighting
- **Hero section** with animated floating badge cards and spinning avatar ring
- **Scrolling marquee** tech strip between hero and about
- **About section** with sticky ID card and info grid
- **Skills section** with tabbed filtering (All / Languages / Frontend / Backend / Tools) and animated progress bars
- **Experience timeline** with vertical line, dot markers, and slide-in cards
- **Projects section** with:
  - Featured wide card (Django Article Portal)
  - 3-column project grid
  - Live filter buttons (All / Full Stack / SQL / ML & Data)
- **Certifications & Achievements** with hover-animated rows and stat cards
- **Contact section** with radial glow and clickable contact cards
- **Scroll reveal animations** on all major elements
- **Fully responsive** — works on desktop, tablet, and mobile

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Markup | HTML5 |
| Styling | CSS3 (Custom Properties, Flexbox, Grid) |
| Scripting | Vanilla JavaScript (IntersectionObserver, DOM events) |
| Fonts | [Syne](https://fonts.google.com/specimen/Syne) + [DM Sans](https://fonts.google.com/specimen/DM+Sans) via Google Fonts |
| Icons | Emoji (no icon library needed) |
| Design Reference | [Picto – Figma Community Template](https://www.figma.com/community/file/1170206889562959306) |

---

## 📂 Sections

| # | Section | Description |
|---|---------|-------------|
| 1 | **Home / Hero** | Name, title, tagline, KPIs, floating badges |
| 2 | **About** | Bio, ID card, education, contact info |
| 3 | **Skills** | Tabbed skill chips with progress bars |
| 4 | **Experience** | Timeline — TechnoHacks Internship & JSpiders Training |
| 5 | **Projects** | 5 projects with filter — Django, E-Commerce, SQL, ML, Data |
| 6 | **Certifications** | 5 certs + LeetCode count + CGPA + Club achievement |
| 7 | **Contact** | Email, phone, LinkedIn CTA |

---

## 🚀 Projects Showcased

### ⭐ Featured
- **Django Article Portal** — Full-stack blog/info portal built with Python & Django (JSpiders training project)

### Grid Projects
- **Employee Management System** — MySQL relational DB with CRUD, JOINs, aggregates
- **E-Commerce Website** — Responsive frontend with dynamic DOM, search & filtering
- **House Price Prediction** — ML model (Decision Tree, 85% accuracy) with Scikit-learn
- **Sales Data Analysis** — Revenue trend analysis & visual reports with Pandas & Matplotlib

---

## 🖥️ How to Run Locally

No build step needed — just clone and open:

```bash
# 1. Clone the repo
git clone https://github.com/your-username/portfolio.git

# 2. Navigate into the folder
cd portfolio

# 3. Open in browser
open index.html
# or on Windows:
start index.html
# or just drag index.html into any browser
```

---

## 🌐 Deployment

Live Link - https://nithin-portfolio-gules.vercel.app/

### GitHub Pages (Recommended — Free)

1. Push this repo to GitHub
2. Go to **Settings → Pages**
3. Under **Source**, select `main` branch and `/ (root)`
4. Click **Save** — your site will be live at:
   ```
   https://your-username.github.io/portfolio/
   ```

### Netlify (Alternative)

1. Drag and drop the project folder onto [netlify.com/drop](https://app.netlify.com/drop)
2. Get an instant live URL — no account needed

### Vercel

```bash
npm i -g vercel
vercel
```

---

## 🎨 Customisation

All personal data is in the HTML itself — easy to edit:

| What to change | Where to find it |
|----------------|-----------------|
| Name, title, bio | `#home` and `#about` sections |
| Contact details (email, phone, LinkedIn) | `#about` info grid + `#contact` cards |
| Skills & proficiency levels | `#skills` — edit `sk-bar` width percentages |
| Experience entries | `#experience` `.exp-entry` blocks |
| Projects | `#projects` — `.proj-feat` (featured) + `.proj-card` (grid) |
| Certifications | `#certifications` `.cert-row` blocks |
| Accent color | `:root` → `--accent: #c8ff00;` |
| Fonts | Google Fonts `<link>` in `<head>` + `--font-h` / `--font-b` variables |

---

## 📄 License

This project is open source and free to use under the [MIT License](LICENSE).

The design is inspired by the **Picto** Figma template by [Templatecookie](https://www.figma.com/@templatecookie), licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).

---

## 🙋 About Me

**Sattu Nithin** — Full Stack Python Developer  
📍 Hyderabad, Telangana, India  
📧 nithins0073@gmail.com  
📱 +91 9014053049  
💼 [LinkedIn](https://www.linkedin.com/in/sattunithin-63b00a286)

> B.Tech CSE & AIML Graduate · JSpiders Trainee · Open to Entry-Level Opportunities

---

*Built with ❤️ and zero frameworks.*
