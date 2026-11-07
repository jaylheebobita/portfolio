# Jaylhee B. Bobita - Personal Portfolio

A fast, responsive, and minimalist personal portfolio web application designed for **Jaylhee B. Bobita**, BSIT student at Data Center College of the Philippines - Bangued.

## 🌿 Design Features & Color System

- **Strict Color Enforcement:**
  - **Light Mode:** Crisp, clean background with gentle pastel **baby green** accents (`#52a681`, `#75be9c`, `#e3f3eb`) for active states, borders, buttons, and highlights.
  - **Dark Mode:** Flat, matte dark background (`#0f172a` / slate-900) with muted, soft green accents.
  - **No Neon & No Glowing Drop-Shadows:** Refined, elegant, and professional look with zero gamer/neon glow.
- **Typography:** Refined, feminine, and modern typography using *Plus Jakarta Sans* and *Outfit*.
- **Dynamic JavaScript Architecture:** Driven by a central `portfolioData` object containing personal info, education, skills, projects, and certificates.
- **Interactive Lightbox/Modal:** Full view of project screenshots (Balai ti Arjud & MCA Cafe) and verified certificates (DICT & Cisco).
- **Responsive Layout:** Optimized for mobile phones, tablets, and large screens.

---

## 🚀 Instant Vercel Deployment

This project is structured as a zero-configuration static site that is 100% compatible with Vercel instant deployment:

### Option 1: Vercel CLI
```bash
npm i -g vercel
vercel
```

### Option 2: GitHub / Git Deployment
1. Push this folder to your GitHub repository:
   ```bash
   git init
   git add .
   git commit -m "Initial portfolio commit"
   git branch -M main
   git remote add origin https://github.com/jaylheebobita/portfolio.git
   git push -u origin main
   ```
2. Import the repository in [vercel.com/new](https://vercel.com/new).
3. Select **Other** as the framework preset and click **Deploy**.

### Option 3: Local Testing
Open `index.html` directly in your browser or run a simple local web server:
- With Python: `python -m http.server 3000`
- With PHP: `php -S localhost:3000`
- With VS Code: Live Server extension
- With XAMPP: Access `http://localhost/Bobita Portfolio/`

---

## 📁 Project Structure

```
Bobita Portfolio/
├── assets/
│   ├── cert-cisco-ai.jpg
│   ├── cert-dict-netiquette.jpg
│   ├── profile.jpg
│   └── projects/
│       ├── balai-ti-arjud/
│       ├── mca-cafe/
│       ├── balai-ti-arjud-thumb.png
│       └── mca-cafe-thumb.png
├── cert1.jpg
├── cert2.jpg
├── profile.jpg
├── project1.jpg
├── project2.jpg
├── index.html
├── vercel.json
└── README.md
```
