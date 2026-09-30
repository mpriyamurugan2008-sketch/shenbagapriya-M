# Shenbagapriya M &mdash; Personal Portfolio Website

A modern, responsive, clean blue-and-white personal portfolio website for **Shenbagapriya M**, Web Designer & B.E. Computer Science and Design student at **SNS College of Technology, Coimbatore**.

Crafted strictly based on her official resume with a fresh blue-and-white design, elegant signature typography, smooth scroll animations, mobile responsiveness, and easy-to-edit modular code.

---

## 🚀 Quick Start

### Option 1: Live Development Server (Vite)
To run the live development server with instant Hot Module Reloading:

```bash
# 1. Install dependencies
npm install

# 2. Start Vite server
npm run dev
```

Visit `http://localhost:5173/` in your browser.

### Option 2: Standalone Static Mode (Zero Dependencies)
You don't even need Node.js installed to view or host this website! Simply double-click `index.html` or open it directly in any browser (Chrome, Edge, Safari, Firefox).

### Option 3: Production Build
```bash
npm run build
```
Creates an optimized production bundle inside `dist/`.

---

## 📁 Project Structure

```
portfolio/
├── index.html                      # Semantic single-page structure (Home, About, Education, Skills, Certifications, Contact)
├── package.json                    # Project configuration & npm scripts
├── vite.config.js                  # Vite server & build configuration
├── README.md                       # Documentation & editing guide
├── public/                         # Public static assets for production
│   └── assets/docs/                # Downloadable resume PDF & original resume graphic
├── assets/
│   ├── css/
│   │   ├── variables.css           # Design tokens, clean blue-and-white theme & midnight dark theme
│   │   ├── base.css                # Modern reset, typography, and accessibility utilities
│   │   ├── components.css          # Buttons, status pill, cards, and toast notifications
│   │   └── style.css               # Section layouts, signature font styling, and responsive media queries
│   ├── js/
│   │   ├── main.js                 # Theme toggler, sticky nav, mobile menu, scroll spy, and animations
│   │   └── contact.js              # One-click copy for email/phone & interactive contact form handler
│   ├── images/
│   │   ├── profile.png             # Official portrait photo extracted and cropped from resume
│   │   └── favicon.svg             # Vector monogram favicon (SM)
│   └── docs/
│       ├── Shenbagapriya_M_Resume.pdf  # Downloadable resume PDF
│       └── Shenbagapriya_M_Resume.png  # High-resolution original resume document
```

---

## 🎨 Sections Included

1. **Home (Hero)**:
   - Status badge: *Available for Web Design & Internships*
   - Handwritten signature styling for *Shenbagapriya M* matching the resume calligraphy
   - Prominent role: **WEB DESIGNER**
   - Exact resume tagline: *Creative mind &bull; Design lover &bull; Future builder*
   - Profile portrait with delicate botanical leaf accents matching the resume aesthetic
   - Quick action buttons: *Get in Touch*, *View Education*, *Download Resume*
   - Highlights bar: SNS College of Technology (2025–2029), 3 Certifications, Coimbatore (Tamil Nadu)

2. **About**:
   - Academic narrative outlining studies at SNS College of Technology, Coimbatore
   - Quick meta cards: College, Degree & Duration, Location, Core Role
   - 3 Feature Pillars: *Creative Mind* (Web Design & UX), *Design Lover* (IBM Design Thinking Practitioner), and *Future Builder* (Programming in Python, C++, C, LeetCode & Generative AI)

3. **Education**:
   - Interactive vertical timeline with glowing nodes:
     - **2025 &ndash; 2029 (Current)**: SNS College of Technology, Coimbatore &mdash; *B.E Computer Science and Design*
     - **2025**: Government Higher Secondary School, Vellithiruppur &mdash; *Higher Secondary Certificate (HSC) &ndash; 75.8%*
     - **2023**: Government Higher Secondary School, Vellithiruppur &mdash; *Secondary School Leaving Certificate (SSLC) &ndash; 77.2%*

4. **Skills**:
   - Categorized cards covering all resume skills:
     - **Programming**: Python (*SCALAR Excellence*), C++, C, Leet Code (*Problem Solving*)
     - **Web & Design**: Web Designer (*Primary Role*), HTML (*Markup & UI*), Design Thinker (*IBM Framework*)
     - **Tools & Office**: MS WORD (*Documentation*), Excel (*Data & Sheets*)

5. **Certifications**:
   - Verified credential cards matching the resume:
     - **SCALAR**: *Certification of excellence for python programming*
     - **IBM**: *Certification of enterprise design thinking and practitioner*
     - **DATABRICKS**: *Generative AI Fundamentals certification*

6. **Contact**:
   - Direct contact info cards with **One-Click Copy** buttons:
     - 📞 Phone: `6379148080` (+91 6379148080)
     - ✉️ Email: `mpriyamurugan2008@gmail.com`
     - 📍 Location: `Coimbatore - 641034`, Tamil Nadu, India
     - 💼 LinkedIn: [https://www.linkedin.com/in/shenbagapriya-m-](https://www.linkedin.com/in/shenbagapriya-m-)
     - 💻 GitHub: [https://github.com/mpriyamurugan2008-sketch](https://github.com/mpriyamurugan2008-sketch)
     - 📄 Resume: Direct link to view image or download PDF
   - Interactive message form with client-side validation and toast notification

---

## ✏️ Easy Customization Guide

- **Edit Text Content**: Open `index.html` and search for any text (e.g. phone number, bio, or links) to change it directly.
- **Change Colors / Theme**: Open `assets/css/variables.css` to modify the primary blue shades (`--primary`, `--secondary`), backgrounds, or font families.
- **Update Profile Photo**: Replace `assets/images/profile.png` with a new square image.
- **Update Resume PDF**: Replace `assets/docs/Shenbagapriya_M_Resume.pdf` and `public/assets/docs/Shenbagapriya_M_Resume.pdf`.

---

## 🌐 Free 1-Click Deployment

### Deploy to GitHub Pages
1. Push this folder to a GitHub repository:
   ```bash
   git init
   git add .
   git commit -m "Launch Shenbagapriya M portfolio"
   git branch -M main
   git remote add origin https://github.com/mpriyamurugan2008-sketch/portfolio.git
   git push -u origin main
   ```
2. In your repo, go to **Settings > Pages**.
3. Under **Build and deployment > Source**, choose `Deploy from a branch` with branch `main` and folder `/ (root)`.
4. Click **Save**. Your site will be live at `https://mpriyamurugan2008-sketch.github.io/portfolio/`.

### Deploy to Vercel / Netlify
Simply import the GitHub repository on [Vercel](https://vercel.com) or drag-and-drop the project folder onto [Netlify Drop](https://app.netlify.com/drop).
