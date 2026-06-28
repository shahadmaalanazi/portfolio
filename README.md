# Shahad AlAnazi — Portfolio Website

A personal portfolio website for Shahad AlAnazi, an Artificial Intelligence student, showcasing projects in Machine Learning, Deep Learning, NLP, and IoT.

🔗 **Live Preview:** [Open `index.html` in any browser.
](https://shahadmaalanazi.github.io/portfolio/)
---



---

---

## 🛠️ Built With

- **HTML5**
- **CSS3** (custom properties, Flexbox, Grid, animations, media queries)
- **Vanilla JavaScript** (no frameworks/libraries)
- **Google Fonts** — Inter
- **Google Apps Script** — backend for the suggestions form

---

## 🚀 How to Run Locally

1. Download/clone all project files into one folder.
2. Make sure all images listed above are present.
3. Open `index.html` directly in your browser — no build step or server required.

---

## 📋 Sections Overview

| Section | ID | Description |
|---|---|---|
| Home | `#home` | Hero intro with photo and title |
| About | `#about` | Short personal/professional summary |
| Projects | `#projects` | Clickable project cards with image gallery modal |
| Skills | `#skills-section` | Technical skill tags |
| Suggestions | `#suggestions` | Feedback form (POSTs to Google Apps Script) |
| Contact | `#contact` | Social and email links |

---

## ✉️ Suggestions Form Setup

The form submits messages via `fetch()` to a Google Apps Script Web App URL using `mode: "no-cors"`. To use your own backend:

1. Replace the URL in the `fetch()` call inside the `<script>` tag with your own Apps Script (or other) endpoint.
2. Ensure your script accepts POST requests with a JSON body: `{ "message": "..." }`.

---

## 📌 Notes / Possible Improvements

- Add form validation feedback (e.g., error states) beyond the success message.
- Add `alt` text to all `<img>` tags for accessibility.
- Consider lazy-loading project images for performance.
- Replace inline image arrays in `onclick` with a JS data array/object for easier maintenance.

---

## 👤 Author

**Shahad AlAnazi**
- LinkedIn: [shahad-alanazi-ma](https://www.linkedin.com/in/shahad-alanazi-ma)
- Email: shahadmaalanazi@gmail.com

---

© 2026 Shahad AlAnazi
