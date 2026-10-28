# Landiqoo website

A static, responsive single-page site (HTML, CSS, vanilla JavaScript). No build step needed.

## Run it (Windows / PowerShell)
Open the folder in VS Code and either:
- double-click `index.html`, or
- run `npx serve .` inside this folder and open the address it prints.

## Files
- `index.html`: page structure (all 12 sections)
- `css/styles.css`: design tokens (colors, fonts) at the top, then each section
- `js/main.js`: portfolio/services data, concept preview dialog, mobile menu, contact form
- `assets/logo-mark.png`: logo mark (transparent). `assets/logo-full.png`: your original logo
- `Landiqoo_Claude_Code_Master_Prompt.txt`: your original plan

## To do before launch
1. Get a free access key at web3forms.com (enter landiqoofounders@gmail.com) and paste it into `WEB3FORMS_KEY` at the top of `js/main.js`.
2. Deploy, then send a test message from the live site and check your inbox (and spam folder).
3. Deploy the folder to Netlify, Vercel, or GitHub Pages.

## Next step: React + Vite + Tailwind
In Claude Code, open this folder and ask it to convert this site into the React/Vite/Tailwind structure from the master prompt, keeping the design as is.
