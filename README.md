# ⚡ Sahan Munasingha — Developer Portfolio

[![Live Site](https://img.shields.io/badge/Live_Site-sahanmunasingha.netlify.app-000000?style=for-the-badge&logo=netlify&logoColor=white)](https://sahanmunasingha.netlify.app/)
[![Built With: Astro](https://img.shields.io/badge/Built_With-Astro_v4-BC52EE?style=for-the-badge&logo=astro&logoColor=white)](https://astro.build/)
[![Styling: Vanilla CSS / Responsive](https://img.shields.io/badge/Design-Responsive_Dark_Mode-ff8c00?style=for-the-badge)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg?style=for-the-badge)](LICENSE)

The source code for my personal engineering portfolio, built to highlight distributed systems architecture, microservices engineering, and full-stack projects. Engineered with Astro for zero-JS-by-default runtime performance, fast static page generation, and optimized media delivery.

---

## 📸 Preview

<div align="center">
  <img src="./public/preview.png" alt="Portfolio Preview" width="850" />
</div>

---

## ✨ Features & Architecture

* **Zero-Runtime Overhead:** Built on Astro's static site generation (SSG) architecture, serving pre-rendered HTML/CSS with instant first-contentful paint (FCP).
* **Curated Technical Case Studies:** Deep dives into featured projects including **PulseCare** (Spring Boot Microservices & K8s) and **Greenvy** (AI-powered SDG 12 Web App).
* **Categorized Competencies:** Segmented skill matrix organizing backend systems, cloud orchestration, web technologies, and QA tools.
* **Optimized Media Pipeline:** Utilizes Astro's native image optimization to compress and convert assets to modern formats on the fly.
* **Accessible & Mobile Responsive:** Fluid responsive layouts with a dedicated mobile drawer navigation and dark-mode aesthetic.

---

## 🛠️ Built With

* **Core Framework:** [Astro](https://astro.build/) (Component-driven static site generator)
* **Language:** TypeScript / JavaScript (ES6+)
* **Styling:** Scoped CSS Variables, Glassmorphism, and Fluid Media Queries
* **Iconography:** [Remix Icon](https://remixicon.com/)
* **Hosting & CI/CD:** [Netlify](https://www.netlify.com/) (Continuous deployment via GitHub hooks)

---

## 📂 Project Structure

```text
portfolio/
├── public/
│   ├── favicon.svg          # Favicon asset
│   ├── resume.pdf           # Publicly downloadable CV
│   └── preview.png          # Repo thumbnail preview
├── src/
│   ├── assets/              # Optimized profile pictures & local media
│   ├── components/
│   │   ├── Navbar.astro     # Sticky glassmorphism header & mobile drawer
│   │   ├── Hero.astro       # Introduction, status badge & primary CTAs
│   │   ├── Service.astro    # Core engineering capabilities
│   │   ├── About.astro      # Background, education & technical skills
│   │   └── Projects.astro   # Filterable case studies & repo links
│   ├── layouts/
│   │   └── Layout.astro     # Root layout, meta tags & global font imports
│   └── pages/
│       └── index.astro      # Main landing page
├── astro.config.mjs         # Astro integration & build settings
├── package.json
└── tsconfig.json
