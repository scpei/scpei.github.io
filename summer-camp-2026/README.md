# AI Foundations Summer Camp 2026 — course page

This is a self-contained static course page intended to live under a personal website, for example at `/summer-camp/`.

## Publish

Copy this entire folder into the public/static area of the personal website. Keep `index.html`, `styles.css`, `script.js`, and `slides/` together so all active links continue to work. The overall course introduction is an interactive HTML presentation under `slides/overall/`. The Day 1–4 notebook and slide buttons are currently placeholders and can be connected to the real class materials shortly before each session.

If the personal website is built with React, Next.js, Hugo, Jekyll, or another framework, the design can also be converted into a native route while keeping the content and styles.

## Local preview

From this folder, run a local static server and open the printed URL in a browser.

```bash
python3 -m http.server 8080
```

## Public/private boundary

Only student-facing notebooks and the overall course PDF are included. Instructor demos, answer keys, TA notes, and internal planning files remain outside this folder.
