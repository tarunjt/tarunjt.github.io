# Simple Editing Guide

This website is a static GitHub Pages portfolio. You do not need to run any build command.

## Files you will usually edit

- `index.html` — homepage content
- `case-cara.html` — CARA case study
- `case-robotaxi.html` — Robotaxi/Test Suite case study
- `case-d2c.html` — D2C WebView case study
- `case-museum.html` — Museum redesign case study
- `case-ehr.html` — Healthcare/EHR case study
- `assets/styles.css` — visual styling, spacing, colors, cards, responsiveness
- `assets/script.js` — tiny JavaScript file; usually no need to edit

## Things to replace first

Search inside the files for these placeholders:

- `your.email@example.com`
- `LinkedIn` link placeholders
- `GitHub` link placeholders
- `resume.pdf`

## Upload rule for GitHub Pages

Upload the files inside this folder directly into your `tarunjt.github.io` repo.
Do not upload the folder as an extra folder.

Correct:

```text
tarunjt.github.io/
├── index.html
├── case-cara.html
├── assets/
└── ...
```

Incorrect:

```text
tarunjt.github.io/
└── ux-portfolio-site-readable/
    ├── index.html
    └── assets/
```

## Editing tip

Use VS Code and install the extension `Prettier - Code formatter`. Then right-click inside a file and choose `Format Document` whenever the code looks messy.
