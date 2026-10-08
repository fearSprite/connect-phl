# Connect Phl — Youth Resource & Application Pipeline

> A lightweight, zero-barrier mobile web application connecting Philadelphia youth and young adults (ages 14–21) directly to local opportunities, paid stipends, and support programs.

---

## 📌 Project Overview

Navigating non-profit programs in Philadelphia is often frustrating—information is scattered across dozens of outdated websites with complex legalese, leaving youth unsure of what they actually qualify for. 

**Connect Phl** solves this by acting as a direct pipeline. Built specifically for phone-first users relying on limited cellular data, the platform strips away forced user sign-ups and complex forms. In under 60 seconds, users can filter programs by exact age and cost, review plain-language eligibility summaries, and jump straight to outbound application portals or request direct human navigator support.

---

## ✨ Key Features

* **Zero-Barrier Open Browsing:** No account registration or login required to search, filter, or view listings.
* **Age-Specific Filtering (14–21):** Dynamically filters out programs youth are legally or structurally ineligible for.
* **Stipend & Cost Toggles:** Quickly isolate paid opportunities, internships, and 100% free community resources.
* **Plain-Language Eligibility Cards:** Deconstructs legal requirements into clear, digestible bullet points.
* **1-Tap Navigator Support:** Built-in help button triggers a 2-field micro-intake form for youth who get stuck or encounter broken links.
* **Low-Bandwidth Mobile Engine:** Zero external heavy libraries—loads instantly on 3G cellular connections and older smartphones.

---

## 🛠️ Tech Stack

* **Frontend:** Vanilla HTML5, Modern CSS3 (CSS Grid, Custom Variables, Mobile-First Responsive UI)
* **Logic & Filtering:** Vanilla JavaScript (ES6+ client-side indexing)
* **Hosting:** Optimized for GitHub Pages, Vercel, or Netlify
* **Dependencies:** None (0 npm dependencies for ultra-fast load times)

---

## 📂 Repository Structure

```text
connect-phl/
├── index.html        # Main HTML layout, accessibility markup, and modal structure
├── styles.css        # Mobile-first design system, design tokens, and layout grid
├── js/
│   ├── data.js       # Vetted program database & eligibility schema
│   └── app.js        # Filter engine, DOM renderer, and modal controller
└── README.md         # Documentation & setup guide
