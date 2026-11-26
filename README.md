# Nelson Sooranad — Actor & Comedian Portfolio

<div align="center">

  [![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-v3-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
  [![WebGL](https://img.shields.io/badge/Graphics-OGL_WebGL-black?style=for-the-badge&logo=webgl&logoColor=white)](https://github.com/oframe/ogl)
  [![License](https://img.shields.io/badge/License-MIT-000000?style=for-the-badge)](LICENSE)

  <p align="center">
    <strong>Official editorial digital portfolio for Nelson Sooranad — Celebrated Malayalam Film Actor & Comedian (known as 'Dragon Paili' in Aadu).</strong>
  </p>

</div>

---

## ✦ Overview

This portfolio showcases the cinema career, television fame, and live stage journey of **Nelson Sooranad** (Kollam, Kerala). Engineered with a monochrome editorial aesthetic, fluid WebGL graphics, and hardware-accelerated horizontal spatial scrolling, it presents his iconic characters and filmography in an immersive web experience.

---

## ✦ Key Sections

### 1. 🎭 Editorial Hero
- Metallic typography header featuring **Nelson Sooranad**.
- Actor credentials (`EST. 2010`, `Sooranad • Kerala`), genre specialties, and stylized headshot.

### 2. 🧭 Horizontal Journey Timeline ("Where I've Been")
- **2000 — 2010: Mimicry & Comedy Stars**: Early stage roots in Kollam and statewide breakthrough on Asianet's landmark *Comedy Stars*.
- **2010 — Present: Malayalam Cinema (50+ Films)**: Debut in *Thaskara Lahala* (2010) and iconic roles in *Spanish Masala*, *Romans*, *Rajadhiraja*, and the cult-classic character **Dragon Paili** in *Aadu* & *Aadu 2*.

### 3. 🌊 Featured Films (OGL WebGL Liquid Carousel)
- Interactive card slider powered by **OGL** (lightweight WebGL engine).
- Highlights *Aadu Series*, *Romans*, and *Spanish Masala*.
- Dynamic modal inspection with film metadata, character details, and box office highlights.

### 4. 📩 Enquiries & Bookings Modal
- Booking channels for feature film casting, international stage shows, brand endorsements, and celebrity guest appearances.

---

## ✦ Running Locally

```bash
# Clone or open directory
cd Neslon-portfolio-main

# Start server using Python
python -m http.server 8080

# Or with npm
npm start
```

Visit `http://localhost:8080` in your web browser.

---

## ✦ How to Host on GitHub (GitHub Pages)

This project consists of pure static web assets (HTML, CSS, JS, images) with relative paths, making it 100% compatible with GitHub Pages out of the box with zero build steps needed!

### Step 1: Initialize Git & Commit
Open terminal in the project directory:
```bash
git init
git add .
git commit -m "feat: Nelson Sooranad actor portfolio"
```

### Step 2: Push to a GitHub Repository
1. Go to [GitHub.com](https://github.com/) and create a **New Repository** (e.g., `nelson-portfolio`).
2. Run the commands shown by GitHub to push your local repository:
```bash
git branch -M main
git remote add origin https://github.com/<YOUR-USERNAME>/nelson-portfolio.git
git push -u origin main
```

### Step 3: Enable GitHub Pages
1. Go to your repository on GitHub.
2. Click **Settings** (tab at the top right).
3. In the left sidebar, click **Pages** (under the "Code and automation" section).
4. Under **Build and deployment**:
   - **Source**: Select `Deploy from a branch`
   - **Branch**: Select `main` and folder `/ (root)`
   - Click **Save**.
5. Wait 1–2 minutes, then refresh the page. Your site will be live at:
   ```
   https://<YOUR-USERNAME>.github.io/nelson-portfolio/
   ```

---

## ✦ License

This project is open-source and available under the [MIT License](LICENSE).
