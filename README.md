# CyberLab Quest — Stage 1 Documentation (Scope + Design)

## 1) Project Scope
**Project Name:** CyberLab Quest  
**Type:** Self-paced learning + lab tracking portal (static HTML5 first, then CSS/JS).  
**Primary Users:** Beginner cybersecurity learners (students / early career).  

### In-Scope (MVP for Weeks 1–2: HTML5)
- Multi-page static site
- Modules page: a structured learning path
- Lab Library page: lab catalog with semantic content and HTML5 UI elements
- Glossary page: definition list + mini self-check form
- About/Contact: scope summary + contact form

### Out-of-Scope (for Week 1–2)
- Saving progress or journal entries
- Real authentication/user accounts
- Backend or database

### Success Criteria (for grading)
- Clear concept and consistent theme across pages
- Strong use of semantic HTML5 tags
- Multiple “distinguished features” present without JS
- 4–6 quality pages, well-structured and accessible

---

## 2) Information Architecture (IA)
**Pages:**
1. `index.html` — Home/Dashboard overview + progress snapshot + journal form  
2. `modules.html` — Learning path + schedule table  
3. `labs.html` — Lab catalog + filter UI + media + template for future JS  
4. `glossary.html` — Key terms + mini check  
5. `about.html` — Project overview + contact form + roadmap  

**Primary Navigation:** Top nav on every page for consistency.

---

## 3) Design Plan (Wireframe-level)
### Global Layout
- Header: title + navigation
- Main: page-specific content grouped in sections
- Footer: copyright

### Accessibility + UX
- “Skip to main content” link on each page
- Use of headings in logical order (h1 → h2 → h3)
- Tables include caption + thead + header scopes

---

## 4) HTML5 Features Used (Week 1–2 focus)
- Semantic structure: `header`, `nav`, `main`, `section`, `article`, `aside`, `footer`
- Disclosure widgets: `details`, `summary`
- Media: `audio`, `video`, `picture`, `source`, `figure`, `figcaption`
- Forms: `fieldset`, `legend`, `input` types (email, number, search), `textarea`, `select`, `datalist`
- Data display: `table`, `caption`, `thead`, `tbody`
- Progress indicators: `progress`, `meter`
- Text semantics: `time`, `abbr`, `code`, `pre`, `kbd`, `samp`, `mark`
- Future JS hook: `template`
- Optional: `dialog` (static open)

---

## 5) Planned Enhancements (Course Progression)
### Week 2–3 (CSS3)
- Responsive layout (mobile-first)
- Consistent spacing/typography scale
- Card UI for modules/labs
- Light/Dark theme (optional)

### Week 4–5 (JavaScript)
- Save journal entries (LocalStorage)
- Filter labs by difficulty/topic
- Completion toggle + dynamic progress updates
- Render labs from JSON using `<template>`

### Optional Database
- User accounts and cloud sync for progress/journal

---

## 6) How to Run
Open `index.html` in a browser. Navigate using the top menu.
