# Zagwe Chinno — Profile Website

A single-page profile site for Zagwe Chinno, Founder & Systems Architect. Static HTML/CSS/JS, no build step — deploy as-is (e.g. GitHub Pages).

## Structure

- `index.html` — hero, story, six-step approach (Diagnose → Architect → Encode → Integrate → Automate → Scale), venture proof points (Kadoo, Voidwear, Quelx), and a "Get in Touch" booking section
- `styles.css` — dark, blueprint-style theme
- `script.js` — footer year only

## Before going live

The booking section embeds a Calendly inline widget pointed at a placeholder URL:

```
https://calendly.com/zagwechinno/30min
```

Update the `data-url` on the `.calendly-inline-widget` element in `index.html` with your real Calendly event link.

The "My Breakthrough" section (right under the hero) expects a headshot at:

```
assets/zagwe-chinno.jpg
```

Add your photo at that exact path — square-ish crop works best, the section frames it as a 1:1 square. If you use a different filename or extension, update the `src` on the `<img>` in the `#breakthrough` section of `index.html` to match.

## Deploying with GitHub Pages

1. Repo Settings → Pages → Source: deploy from branch
2. Pick the branch and `/ (root)` folder
3. Save — the site publishes at `https://<username>.github.io/<repo>/`
