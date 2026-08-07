# Micah Jenkins — Professional Experience

A single-page resume site: professional experience, projects, skills, and education.

Plain HTML, CSS, and self-hosted fonts. No build step, no framework, no dependencies.

## Run locally

```
python3 -m http.server
```

Then open `http://localhost:8000`.

## Structure

```
index.html
styles.css
assets/
  favicon.svg
  image-place-holder.png   (Open Graph card, 1200×630)
  fonts/                   (self-hosted woff2, Latin subset)
```

## Deployment

Served as-is via GitHub Pages from the `main` branch, `/ (root)` folder. `.nojekyll` is committed so files are served without Jekyll processing.
