# jajehgroup.com

Static site for Jajeh Group, hosted on GitHub Pages (repo: overtaxedgoose/jajehgroup.com).
Migrated from GoDaddy Websites+Marketing in August 2026.

## Structure
- Plain HTML/CSS, no build step. Pushing to `main` deploys automatically via GitHub Pages.
- `index.html` — home (founder story + ventures grid)
- `529.html` — unlisted page at /529: Ugift 529 gifting links for the kids (not in nav, linked privately)
- `tax.html` — unlisted page at /tax: embedded Google Form tax organizer
- `assets/css/style.css` — all styling; fonts are Lusitana (headings) + Lato (body) via Google Fonts
- `CNAME` — custom domain; do not delete

## Brand notes (from Patrick's designer)
- The logo font is Flama Condensed (Bold and Light). Reserve it for the logo itself — do not use
  it for site text. Site typography is a simple, non-condensed sans (Lato) so the logo owns the
  visual hierarchy. Same guidance applies to Jajeh Financial.
- Original logo files: https://drive.google.com/drive/folders/0Bwh1qJPtBF-Jcjh1T2NiTF9HaXc?resourcekey=0-hvT00l0A9ZhAj9L81ZgsoQ
- Venture tiles: if a logo contains the company's full name, do not repeat the name as text below it.

## Rules
- URL paths /529 and /tax must keep working (GitHub Pages serves 529.html at /529).
- DNS is at GoDaddy; email is Google Workspace — never suggest changing NS/MX/TXT records.
- Keep /529 and /tax out of the site nav; they are intentionally unlisted.
