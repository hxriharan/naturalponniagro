# Natural Ponni Agro – Simple Website

A lightweight, single‑page website for **Natural Ponni Agro Products** (இயற்கை பொன்னி அக்‌ரோ தயாரிப்புகள்).

## Quick Start

1. Open the `index.html` file in a browser to preview locally.

## Deploy Options

### GitHub Pages (free)
1. Create a new repo (e.g., `natural-ponni-agro`).
2. Upload all files in this folder to the repo root.
3. In repo **Settings → Pages**, set **Source** to **Deploy from a branch**, Branch: `main` (or `master`), Folder: `/root`.
4. Wait ~1 minute. Your site will be available at `https://<your-username>.github.io/natural-ponni-agro/`.

### Netlify (very easy)
1. Go to https://app.netlify.com/ and drag‑and‑drop this folder.
2. Netlify will give you a public URL immediately. You can later add a custom domain.

### Custom Domain
- Buy a domain (e.g., from Namecheap).
- Point DNS `A` or `CNAME` to your host (GitHub Pages / Netlify guides available).
- Update the JSON‑LD in `index.html` field `"url"` with your actual domain.

## Customize
- Edit address, phone, email in the **Contact** section.
- Replace/optimize images under `/assets`.
- Add more products inside the `#products` section.

## Notes
- No backend is required. The contact form uses `mailto:`; you can replace with a Google Form link or WhatsApp.
