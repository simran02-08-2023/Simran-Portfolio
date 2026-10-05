# Simran Singh — Portfolio

Personal portfolio site for Simran Singh, a Computer Science undergraduate
(B.Tech CSE, 2024–2028) building toward a career as a Java backend / DevOps
engineer. Built from scratch with plain HTML, CSS and JavaScript — no
frameworks, no build step.

**Live site:** _add your deployed URL here once it's live (e.g. GitHub Pages)_

---

## About

The site is a single-page portfolio (`index.html`) with dedicated deep-dive
pages for each featured project. It covers:

- **Hero** — intro, rotating role tagline, resume download, social links
- **About** — quick bio and stats (projects, certifications, technologies)
- **What I Do** — core focus areas (backend, distributed systems, databases,
  DevOps, data/AI, full-stack web)
- **Portfolio** — project grid with hover previews, linking out to individual
  project pages
- **Resume** — tabbed timeline (Education / Skills / Experience)
- **Certifications** — IBM SkillsBuild and Deloitte credentials
- **Contact** — email, GitHub, LinkedIn

## Tech Stack

- HTML5 / CSS3 (hand-written, no CSS framework)
- Vanilla JavaScript (typing effect, scroll reveal, tabs, lightbox, mobile nav)
- [Font Awesome](https://fontawesome.com/) for icons
- Google Fonts — Plus Jakarta Sans & Inter

## Project Structure

```
Simran-Portfolio-main/
├── index.html              # Homepage
├── rate-limiter.html       # Distributed Rate Limiter — project page
├── bank.html                # Bank Management System — project page
├── deepthought.html         # DeepThought Lead — project page
├── climate.html              # India Climate Twin — project page
├── crop.html                 # AI Crop Health Detector — project page
├── batchpulse.html           # BatchPulse — project page
├── lost-found.html           # Lost & Found Intelligent Matching System — project page
├── style.css                 # Site-wide styles
├── script.js                  # Site-wide interactivity
├── assets/                    # Profile photo, resume PDF
├── images/                    # Project screenshots, organized by project
└── videos/                    # Project demo clips
```

## Featured Projects

| Project | Stack | Repo |
|---|---|---|
| Distributed Rate Limiter | Java, Spring Boot, Redis, Docker, Lua | [GitHub](https://github.com/simran02-08-2023/distributed-rate-limiter) |
| Bank Management System | Java, Swing, JDBC, MySQL | [GitHub](https://github.com/simran02-08-2023/Bank-Management-System) |
| DeepThought Lead | Python, SQL, Power BI | [GitHub](https://github.com/simran02-08-2023/deepthought-lead-gen-sa1) |
| India Climate Twin | Python, XGBoost, Streamlit | [GitHub](https://github.com/simran02-08-2023/nexacore-climate-twin) |
| AI Crop Health Detector | Python, OpenCV | [GitHub](https://github.com/simran02-08-2023/Agri-Tech_Prototype) |
| BatchPulse *(in progress)* | Next.js, TypeScript, Supabase | [GitHub](https://github.com/simran02-08-2023/batchpulse) |
| Lost & Found Intelligent Matching System *(in progress)* | Java, Jakarta Servlets, JSP, JDBC, MySQL, Tomcat | [GitHub](https://github.com/simran02-08-2023/lost-found-system) |

## Running Locally

No build tools or dependencies required.

```bash
git clone https://github.com/simran02-08-2023/Simran-Portfolio.git
cd Simran-Portfolio
```

Then just open `index.html` in a browser, or serve it locally:

```bash
# Python
python3 -m http.server 8000

# Node (if you have the `serve` package)
npx serve .
```

Visit `http://localhost:8000`.

## Deploying (GitHub Pages)

1. Push this repo to GitHub.
2. Go to **Settings → Pages**.
3. Under **Source**, select the `main` branch and `/ (root)`.
4. Save — your site will be live at `https://<username>.github.io/<repo-name>/`.

## Contact

- **Email:** singhanchal33141@gmail.com
- **GitHub:** [github.com/simran02-08-2023](https://github.com/simran02-08-2023)
- **LinkedIn:** [linkedin.com/in/simran-singh1128](https://www.linkedin.com/in/simran-singh1128/)

---

© 2026 Simran Singh. All rights reserved.
