# Frontend Playground — Small UI Demos

Tiny, focused UI demos to practice fundamentals:
- **Forms & validation**
- **Fetch / pagination**
- **Responsive layout**
- **Accessible UI components**

> Goal: show clean, vanilla HTML/CSS/JS with good UX and accessibility.

---

## Live
- **Site:** https://nkuznetsov-dev.github.io/frontend-playground/  

---

## Tech & approach
- **Stack:** HTML, CSS, JavaScript (no framework)
- **Style:** semantic markup, BEM-ish class names, mobile-first CSS
- **A11y:** keyboard support, labels, roles/aria where needed
- **Perf:** no heavy dependencies, images optimized

---

## Structure (planned)
- frontend-playground/  
  - demos/  
    - 01-forms-validation/  
      - index.html  
      - styles.css  
      - main.js  
    - 02-fetch-pagination/  
      - index.html  
      - styles.css  
      - main.js  
    - 03-components-gallery/  
      - index.html  
      - styles.css  
      - main.js  
  - shared/  
    - reset.css  
    - utils.js  
  - assets/  
    - images/  

**Naming convention**
- Demos live under `demos/<NN>-<slug>/`
- Each demo is self-contained (`index.html`, `styles.css`, `main.js`)
- Shared helpers go to `shared/`

---

## Run locally
Any static server is fine:
```bash
# Python
python -m http.server 8000

# or Node
npx serve .
```

Then open http://localhost:8000/demos/01-forms-validation/.
