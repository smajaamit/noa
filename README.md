# Noa ♥ 25

An interactive birthday experience for Noa's 25th birthday.

## Experience
The site is designed as a mobile-first, cinematic story rather than a conventional landing page. It includes a full-screen opening, progressive scroll reveals, relationship timeline, interactive memory gallery with lightbox, a hidden reveal, a live countdown to 09.09.2027, and a personal letter.

## UX principles
- Mobile-first responsive layout
- 44px+ touch targets and clear focus states
- Reduced-motion support
- Semantic RTL Hebrew structure
- Lazy-loaded gallery images
- Layout-stable aspect ratios
- Keyboard/Escape support for the lightbox
- Safe-area-aware hero and controls
- Lightweight vanilla HTML/CSS/JS, no framework dependency

## Photos
Place the final photo files in `/images`. The HTML already references the planned filenames. Before publishing personal photos publicly, strip EXIF/GPS metadata and optimize image dimensions/quality.

## Structure
```
/
├── index.html
├── images/
├── .claude/skills/
├── .github/workflows/pages.yml
└── .nojekyll
```

## Publishing
GitHub Pages deploys from `main` using the Pages workflow.

Expected URL:
`https://smajaamit.github.io/noa/`

## Final QA
After the final images are uploaded, verify the live deployment on iPhone/mobile, desktop, image loading, lightbox behavior, countdown, reduced motion, sharing preview and Core Web Vitals.

Made with love for Noa.
