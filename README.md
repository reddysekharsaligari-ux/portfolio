# Saligari Reddy Sekhar Portfolio

A modern, responsive personal portfolio website built with HTML5, CSS3, and vanilla JavaScript.

## Files included

- `index.html` — main page structure and content
- `style.css` — styling, responsiveness, theme system, and animations
- `script.js` — navigation, theme toggle, reveal animations, and form validation
- `assets/images/` — local placeholder images for the profile and project cards
- `assets/Saligari_Reddy_Sekhar_Resume.pdf` — place your resume here when ready

## Folder structure

```text
portfolio/
├── index.html
├── style.css
├── script.js
├── README.md
├── assets/
│   ├── Saligari_Reddy_Sekhar_Resume.pdf   # Add your resume PDF here
│   └── images/
│       ├── profile-placeholder.svg
│       ├── college-resto.svg
│       ├── calculator.svg
│       ├── weather-app.svg
│       ├── todo-app.svg
│       └── favicon.svg
└── .gitignore (optional)
```

## How to run locally

1. Open the project folder in VS Code.
2. Install the Live Server extension if you do not already have it.
3. Right-click on `index.html`.
4. Select `Open with Live Server`.
5. Your browser should open the portfolio website automatically.

Alternatively, use the VS Code command palette:

- Press `Ctrl + Shift + P`
- Type `Live Server: Open With Live Server`

## Where to add your real content

- Profile photo: `assets/images/profile-placeholder.svg` (replace with your real image file or rename it)
- Resume PDF: `assets/Saligari_Reddy_Sekhar_Resume.pdf`
- Project screenshots: `assets/images/`
- GitHub URLs: update the project card links in `index.html`
- Live demo URLs: update the project card buttons in `index.html`

## Notes

- The project uses a placeholder favicon and placeholder images so you can personalize them later.
- External links are set to open safely in a new tab.
- The contact form validates user input and uses a `mailto:` action until a backend service such as Formspree or EmailJS is connected.
