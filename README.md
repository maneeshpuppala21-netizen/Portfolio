# Maneesh Puppala &mdash; Student Portfolio

A clean, personal portfolio website built with pure **HTML5** and **CSS3** (no JavaScript, no frameworks, no external libraries) for a first-year college web development assignment.

---

## Folder Structure

```
portfolio/
│
├── index.html
│
├── css/
│   ├── base.css
│   ├── navbar.css
│   ├── hero.css
│   ├── about.css
│   ├── skills.css
│   ├── projects.css
│   ├── education.css
│   ├── achievements.css
│   ├── contact.css
│   ├── footer.css
│   ├── animations.css
│   └── responsive.css
│
└── README.md
```

---

## Modular Stylesheet Architecture

The styles are organized into 12 simple, modular CSS files loaded in dependency order:

1. **`css/base.css`** &mdash; *Base Styles & Design Tokens*
   - Clean dark palette variables (`--bg`, `--surface`, `--accent`, `--border`), reset, typography, base button styles, and form element baselines.

2. **`css/navbar.css`** &mdash; *Navigation Bar*
   - Sticky header container, Flexbox layout for logo and navigation links, and simple hover states.

3. **`css/hero.css`** &mdash; *Hero Section*
   - Simple intro layout, name heading, student title, brief intro paragraph, and call-to-action buttons.

4. **`css/about.css`** &mdash; *About Me Section*
   - Two-column layout pairing a personal bio paragraph with a neat metadata sidebar (Course, College, Location, Academic Period).

5. **`css/skills.css`** &mdash; *Skills Section*
   - Simple CSS Grid (`repeat(auto-fill, minmax(170px, 1fr))`) displaying skills as clean tags without exaggerated buzzwords.

6. **`css/projects.css`** &mdash; *Projects Section*
   - Honest, minimal card layout highlighting the Student Portfolio Website project with tech tags and links.

7. **`css/education.css`** &mdash; *Education Section*
   - Clean vertical layout with subtle accent borders for academic milestones (Scaler School of Technology, Kota's Bansal Classes, St. Francis).

8. **`css/achievements.css`** &mdash; *Achievements Section*
   - Simple, honest status box representing first-year learning in progress.

9. **`css/contact.css`** &mdash; *Contact Section*
   - Straightforward two-column layout for direct contact details and a simple message form.

10. **`css/footer.css`** &mdash; *Footer*
    - Simple bottom border, brand text, direct profile links, and copyright notice.

11. **`css/animations.css`** &mdash; *Animations*
    - One subtle page entrance fade (`fadeIn`) and `prefers-reduced-motion` accessibility support.

12. **`css/responsive.css`** &mdash; *Responsive Media Queries*
    - Breakpoints for Tablet (`max-width: 900px`) and Mobile (`max-width: 600px` down to 375px) ensuring no horizontal scrolling on smaller screens.

---

## How to Run & Preview

1. Open `index.html` in any web browser.
2. In **VS Code**, use the **Live Server** extension by right-clicking `index.html` and choosing **"Open with Live Server"**.
