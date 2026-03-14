# goit-advancedjs-hw-01

Homework #1 for the GoIT Advanced JavaScript course. Built with [Vite](https://vitejs.dev/).

## Tasks

### 1 — Image Gallery

**Page:** `src/1-gallery.html` | **Script:** `src/js/1-gallery.js`

Renders a gallery of images from a hardcoded array and adds lightbox functionality using [SimpleLightbox](https://simplelightbox.com/). Clicking any image opens the full-resolution version in an overlay with alt-text captions.

### 2 — Feedback Form with LocalStorage

**Page:** `src/2-form.html` | **Script:** `src/js/2-form.js`

A feedback form with email and message fields. Input is persisted to `localStorage` via a throttled handler (500 ms, using [lodash.throttle](https://lodash.com/docs/#throttle)) so the draft survives page reloads. On submit, the form is validated and the saved state is cleared.

## Getting started

```bash
npm install
npm run dev
```

Open [http://localhost:5173](http://localhost:5173) in your browser.

## Scripts

| Command | Description |
|---|---|
| `npm run dev` | Start dev server |
| `npm run build` | Build for production |
| `npm run preview` | Preview production build |

## Dependencies

- [simplelightbox](https://simplelightbox.com/) — lightbox for the gallery
- [lodash.throttle](https://lodash.com/docs/#throttle) — throttle form input handler

## Deploy

The project is automatically built and deployed to GitHub Pages (`gh-pages` branch) on every push to `main` via GitHub Actions.

Live: [https://mykolamasiuk.github.io/goit-advancedjs-hw-01/](https://mykolamasiuk.github.io/goit-advancedjs-hw-01/)
