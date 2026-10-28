# Revathy's portfolio

One file: `index.html`. No build step.

## Add your photo
Put a portrait photo in this folder named exactly `photo.jpg` (roughly 4:5, at least 800 px tall).
It appears in the dossier polaroid, and as the hero image if a visitor's browser can't run 3D.

## Files
- `index.html`: the whole page.
- `three.min.js`: the 3D library for mini-Revathy. Keep it next to `index.html`.
- `Revathy_Radhakrishnan_Resume.pdf`: the "Download my resume" file. Replace it with the same name to update.
- `showcase/*.jpg`: walkthrough frames of the live tools (22 frames, 1 to 4 per tool), with company, customer and contact names blurred. Captured 27 Oct 2026 from saved results only; the Data Cleaner frames use a dummy file. To re-capture after a tool changes, the scripts are in this session's scratchpad (`showcase/walk.cjs`, `walkfix.cjs`).

## Put it online (free)
- **Netlify Drop:** go to https://app.netlify.com/drop and drag this whole `portfolio` folder onto the page. You get a link at once; sign up to keep it and pick a name.
- **GitHub Pages:** create a public repo on your own GitHub account (not the company one), upload `index.html` and `photo.jpg`, then Settings → Pages → Deploy from branch `main`.
- **Custom domain:** both of the above let you connect one later (for example `revathy.dev`).

## Before you share it
- The "Live tools" section shows screens of Vegam's internal tools, plus internal numbers (account counts, the focus-list size, Claude spend). Get an OK from Vegam before the page goes public.
- The resume PDF includes your phone number. Anyone who downloads it will have it.
- The dossier links to `event-radar-sooty.vercel.app` and `gtm-data-flow.vercel.app`. If either calls Gemini, Claude or another paid API with a company key, anyone with the link can spend those credits. Check, or remove the links.
- The "Ongoing investigations" list includes personal goals (fitness, finances). Remove any you don't want recruiters to read.

## What's on the page
Hero with the 3D mini-Revathy → Personal dossier → The receipts (numbers) → The GTM machine → Tool trading cards → Cost receipt → Patch notes (experience) → Side quests → Contact.

Mini-Revathy: drag her, poke her, punch her in the contact section to copy the email, and leave her alone for 20 seconds to watch her nap. She changes outfit in every section. Easter eggs: type `hire`, or click the logo five times.
