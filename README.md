# ai-prompt-assistant
AI Prompt Assistant (Chrome extension): guide, setup, release notes, privacy policy and FAQ

This repository is the public website for the AI Prompt Assistant Chrome extension, served by GitHub Pages at <https://yck2024.github.io/ai-prompt-assistant/>. Get the extension from the [Chrome Web Store](https://chromewebstore.google.com/detail/ai-prompt-assistant/aakmnieacpcmnfnljndefdocpcoajjoe).

## Pages

- `index.html`: what `//` does, features and supported sites
- `setup.html`: install, first prompts, Google Drive backup and sync, adding your own sites
- `release-notes.html`: what's changed
- `privacy.html`: privacy policy
- `faq.html`: FAQ and support

## Editing

The site is plain HTML and CSS with no build step and no JavaScript. Every page shares the same header and footer, so update all five pages when you change one. Styles live in `assets/css/site.css`, which uses the "Pocket notebook" brand colours. Links are relative so the site works under the `/ai-prompt-assistant/` path. `.nojekyll` tells GitHub Pages to serve the files as they are.

The Nunito and Inter fonts in `assets/fonts/` are under the SIL Open Font License (see `OFL-Nunito.txt` and `OFL-Inter.txt`).
