# Scholarshipped 🎓

**Scholarshipped** is a scholarship finder built for UTEP (University of Texas at El Paso) students. The idea behind the name is simple — the right scholarship finds *you*. Matched with you, built for Miners.

---

## Features

- **Find My Match Quiz** — A short 5-question questionnaire that asks about your GPA, major, financial need, student status, and first-generation status. At the end, it ranks your top 5 scholarship matches with a visual match score.
- **Browse & Search** — A full scholarship listing with a live search bar to filter by name, major, or keyword.
- **Category Sidebar** — Filter scholarships by field of interest including Nursing, IT & Tech, Engineering, Business, Arts & Design, Education, Science, Pre-Law, Athletics, and First-Gen.
- **Scholarship Detail Modal** — Click any card to see full details including award amount, GPA requirement, need-based status, and a direct link to UTEP's Financial Aid page.

---

## Tech Stack

- **React** (with Hooks)
- **Vite** (development server)
- **Plain CSS-in-JS** (no external UI library)

---

## Getting Started

```bash
# 1. Create a Vite + React project
npm create vite@latest scholarshipped -- --template react
cd scholarshipped
npm install

# 2. Replace src/App.jsx with the scholarshipped.jsx file

# 3. Start the dev server
npm run dev
```

Then open **http://localhost:5173** in your browser.

---

## Customization

- To change colors, search for hex values like `#0a0e17` (background) or `#ff5c35` (accent orange) in `App.jsx` and replace them.
- To add scholarships, find the `SCHOLARSHIPS` array near the top of `App.jsx` and add a new entry following the same structure.
- To add a new category, add it to both the `CATEGORIES` array and use the matching `category` id in any scholarship entry.

---

## Built For

University of Texas at El Paso (UTEP) · El Paso, TX
