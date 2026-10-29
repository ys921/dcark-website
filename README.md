# DC Ark — Landing Page

Static site (plain HTML/CSS/JS, no build step).

## Deploy to Vercel
**Option A — drag & drop:** vercel.com → Add New → Project → upload this folder.
**Option B — GitHub:** push this folder to a repo, import it on Vercel. Framework preset: **Other**. Build command: *(empty)*. Output directory: `./`.
**Option C — CLI:** `npm i -g vercel` then run `vercel --prod` inside this folder.

## Files
- `index.html` — the whole page (styles and script inline)
- `assets/` — logo, product and building images extracted from the company profile
- `vercel.json` — clean URLs + long cache for assets

## Easy edits
- Phone / address: search `2020 555` and `Bukit Minyak` in `index.html`
- Industries: search `class="ind"`; brand names: search `marquee`
