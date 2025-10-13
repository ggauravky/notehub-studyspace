# Notes Hub

A small, responsive static website that organizes and provides study notes in a simple, user-friendly layout.

## Overview

Notes Hub is a lightweight HTML/CSS site intended to host and link to categorized notes (School subjects, Semesters, etc.). It's styled with a single `style.css` file and built to be easy to extend.

It is a notes hub — here we organize and manage notes and points in a clear, improved way so you can find and use study material faster.

## Features

- Minimal, clean UI using CSS only
- Responsive navigation and notes container
- Re-usable note cards with "Read More" links
- Google Fonts (Poppins) included for a modern look

## Repository structure

```
notehub-studyspace/
├─ index.html           # Home page
├─ style.css            # Main stylesheet
├─ about/               # Site about page(s)
│  └─ about.html
├─ didea.tldr
├─ gidea.tldr
├─ nidea.tldr
```

## How to view locally

1. Open `index.html` in your browser (double-click or right-click > Open with > your browser).
2. Or serve the folder with a simple HTTP server. Example using Python 3 (from the project root):

```powershell
python -m http.server 8000
# then open http://localhost:8000
```

## Recommended next improvements

- Move inline styles (e.g., the blue horizontal rule) into `style.css` and use semantic classes.
- Add more pages and organize notes into subfolders by subject/semester.
- Add accessibility improvements (alt text, ARIA where needed, skip links).
- Add tests or automated build steps if the project grows.

## Contributing

1. Fork the repository.
2. Create a branch for your feature: `git checkout -b feature/name`.
3. Make changes and commit: `git commit -m "Add feature"`.
4. Push and open a PR.

## License

This repository is available under the MIT License. See `LICENSE` for details.
