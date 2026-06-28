# EarthSolar

A simple website about solar panels and a project to build a smart, efficient solar panel system.

## Live site

Once GitHub Pages is enabled, the site will be available at:

**https://nityaaverma.github.io/earthsolar/**

## Project structure

```
earthsolar/
├── index.html       # Home page (three content sections)
├── css/
│   └── style.css    # Styles and layout
└── README.md
```

## Local preview

From the repository root, run a local server:

```bash
python3 -m http.server 8000
```

Then open [http://localhost:8000](http://localhost:8000) in your browser.

Alternatively, open `index.html` directly in a browser.

## GitHub Pages setup

1. Push this repository to the `main` branch on GitHub.
2. Go to **Settings → Pages** in the repository.
3. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
4. Choose branch **main** and folder **/ (root)**.
5. Click **Save**. The site will be published within a few minutes.

## Editing content

All page text lives in `index.html`. Update the three sections there:

- **Introduction to Solar Panels** — general background on solar energy
- **My Project** — details about the smart solar panel project
- **Description** — broader project context and links

Styles can be adjusted in `css/style.css`.
