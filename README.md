# Mikee's Monsterverse

[![CC BY-NC 4.0](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc/4.0/)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![No JavaScript](https://img.shields.io/badge/JavaScript-None-red.svg)]()

**[View Demo](https://monsterverse.mikeenavales.xyz)**

A collection of kaiju (giant monsters) curated by Mikee. This website showcases both classic kaiju and AI-generated original monsters.

## Story

This project started as a father-and-son bonding activity. Mikee loves kaijus, and together we created this website to showcase his favorite monsters.

The goal? When Mikee is ready to learn coding, this will be his first project to maintain and grow as a contributor. That's why we built it with pure semantic HTML and CSS — no JavaScript, no frameworks — just the fundamentals that every web developer should learn first.

## Features

- Pure semantic HTML5
- CSS styling (no frameworks)
- No JavaScript
- Responsive design
- Accessible markup

## Project Structure

```
mikee-monsterverse/
├── index.html              # Homepage
├── 404.html                # Error page
├── styles.css              # Global stylesheet
├── contents/               # Monster contents
│   ├── ai-generated/       # Original AI-generated kaiju
│   ├── classics/           # Classic kaiju
│   └── my-collection/      # Personal collection
├── images/                 # Shared images (favicon, etc.)
├── fonts/                  # Web fonts
├── LICENSE                 # License file
├── README.md               # This file
└── TRACKER.md              # Content tracker
```

## How to Run

Simply open `index.html` in your web browser, or use a local server:

```bash
npx live-server
```

Then visit `http://localhost:8080` in your browser.

## Adding New Monsters

1. Create a new folder under the appropriate category (e.g., `contents/ai-generated/monster-name/`)
2. Add the monster's image as `monster-name.jpeg`
3. Create an `index.html` file for the monster's page
4. Update the category index page to include the new monster

## Contributing

Contributions are welcome! Whether you want to fix a bug, improve the styling, or suggest new features — feel free to open an issue or submit a pull request.

This project is intentionally simple and beginner-friendly. Keep it that way.

## License

This project is licensed under [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/).

You can share and adapt with attribution for non-commercial purposes.
