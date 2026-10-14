# vegardbratrok-cloud.github.io

Personal portfolio website for Vegard Bratrok — a single-page site built with plain HTML and Tailwind CSS (loaded via CDN, no build step required).

## Running locally

Since this is a single static `index.html` file, you have a couple of options:

**Option 1 — Just open it**
Double-click [index.html](index.html), or open it in a browser directly (`open index.html` on macOS).

**Option 2 — Local server (recommended, avoids any CORS/path quirks)**
```bash
# Using Python
python3 -m http.server 8000
# then visit http://localhost:8000

# Or using Node (if you have npx available)
npx serve .
```

## Deploying

Since the repo is named `vegardbratrok-cloud.github.io`, pushing `index.html` to the `main` branch will publish it automatically via GitHub Pages at `https://vegardbratrok-cloud.github.io`.

## Things to fill in before publishing

Search the file for bracketed placeholders like `[ Add LinkedIn URL ]` and replace them with real content:

- Professional photo in the hero section (replace the `[ Photo ]` placeholder `div` with an `<img>` tag)
- Email address, LinkedIn URL, GitHub URL, and Thalk link in the **Contact** section
- `resume.pdf` — add the actual file to this folder so the "Download Résumé" button works
- Dates for each role in the **Professional Experience** section
- Project screenshots and links in the **Projects & Portfolio** section
- Any additional academic honors in the **Education** section
- Optional personal essays/reflections in the **Beyond the Résumé** section