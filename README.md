# Urmit Patel — Personal Resume Website

Professional executive portfolio and personal resume website for **Urmit Patel** — Enterprise Solutions Architect, Senior Data Engineer, and Senior Developer.

---

## 🌟 Key Features

- **Clean & Modular Architecture:** Built with semantic HTML5, modular CSS design tokens, and lightweight vanilla JavaScript.
- **Fluid Desktop & Mobile Responsiveness:** Fully responsive across all breakpoints (ultrawide monitors, laptops, tablets, and smartphones) using fluid typography (`clamp()`) and flexible CSS grid/flexbox layouts.
- **Executive Dark & Light Mode:** Toggle seamlessly between an executive Dark Mode and a crisp Light Mode with system preference detection and LocalStorage persistence.
- **Dedicated Three Pillars of Expertise:** Clear visual and narrative breakdown of Urmit's triad capabilities:
  1. Senior Software Developer (15 Years)
  2. Solutions Architect
  3. Data Engineer
- **Experience Timeline:** Detailed milestones across **CIBC Bank**, **ING Bank**, and **Deutsche Bank** (Tata Consultancy Services, 2011 – Present).
- **Flagship Project Deep-Dives:** Highlighting core banking transformations, Databricks Lakehouse migrations, Hungary Instant Payments, and legacy decommission initiatives.
- **Certifications & Direct Credly Badges:** Direct visual badges for Databricks, AWS Solutions Architect, AWS Developer, Microsoft Azure, GitHub Actions & Copilot, and Professional Scrum Master™ I (PSM I), linked directly to [Credly Verification](https://www.credly.com/users/urmitpatel).
- **Print / PDF Optimized:** Dedicated `@media print` stylesheet that transforms the page into an executive 2-page ATS-friendly PDF resume when clicking "Resume PDF" or pressing `Ctrl + P`.
- **Zero Runtime Dependencies:** Loads instantaneously with zero external build steps or heavy node modules.

---

## 📁 Project Directory Structure

```
Resume/
├── assets/
│   └── images/
│       └── urmit-patel.jpg      # Profile headshot extracted from resume
├── css/
│   └── styles.css               # Design system, fluid layout, dark/light themes, print CSS
├── js/
│   └── main.js                  # Theme switcher, mobile menu, scrollspy, interactive filters
├── index.html                   # Complete semantic website markup
└── README.md                    # Documentation & deployment guide
```

---

## 🚀 How to View Locally

You can open the website directly in any web browser without needing any web server:
1. Navigate to this folder in Windows File Explorer.
2. Double-click **`index.html`** to open it in Chrome, Edge, Brave, or Firefox.

Or run a local static server if preferred:
```powershell
# Using Python (if available):
python -m http.server 8080

# Using npx (if Node.js is installed):
npx serve .
```

---

## 🌐 Free 1-Click Deployment Options

### Option 1: GitHub Pages (Recommended)
1. Initialize git and push to GitHub:
   ```bash
   git init
   git add .
   git commit -m "Initial commit of personal resume website"
   git remote add origin https://github.com/<your-username>/<repo-name>.git
   git push -u origin main
   ```
2. Go to **Settings > Pages** in your GitHub repository and set the branch to `main` and folder to `/ (root)`.
3. Your website will be live at `https://<your-username>.github.io/<repo-name>/`.

### Option 2: Netlify / Vercel
- Simply drag and drop this `Resume` folder into [Netlify Drop](https://app.netlify.com/drop) or deploy via Vercel CLI for instant global CDN hosting with your own custom domain.
