# PULSEFIT — Static One-Page Gym Website Demo

A premium, fully responsive static website built with plain HTML, CSS and JavaScript. No framework, build command, backend or database is required.

## Files

- `index.html` — page structure and SEO tags
- `styles.css` — complete responsive styling
- `script.js` — editable gym data, dynamic cards, WhatsApp links, form validation and interactions

## Open locally

Double-click `index.html`, or run a small local server:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## Customize for a gym

Open `script.js` and edit the `siteConfig` object at the top.

Update:

- business name and tagline
- WhatsApp number
- phone number
- email
- address and opening hours
- Google Maps URL
- programs
- facilities
- trainers
- membership plans
- testimonials
- FAQs

### WhatsApp number format

Use the full country code without `+`, spaces or hyphens.

Example:

```js
whatsappNumber: "919876543210"
```

### Phone link format

```js
phoneLink: "+919876543210"
```

## Replace images

All image URLs are stored in `siteConfig` inside `script.js`. Replace any image URL with:

- a local path such as `assets/hero.webp`
- your own CDN link
- an optimized WebP or AVIF image URL

For best performance, use images around 1200–1600 px wide and compress them before upload.

## Change colors

Open `styles.css` and edit the variables near the top:

```css
:root {
  --bg: #070906;
  --accent: #b8ff35;
  --text: #f4f7ef;
}
```

## Free-trial form

The form validates required fields and opens WhatsApp with a formatted enquiry message. It does not require a backend.

## Deploy

Upload the folder to any static host, including:

- Netlify
- Vercel
- GitHub Pages
- Cloudflare Pages
- cPanel/public_html

For a custom domain, connect the domain in your hosting provider and update the site metadata in `index.html`.

## Important demo note

PULSEFIT is fictional. Trainer names, testimonials, plans, facility details and contact information are placeholders and should be replaced before using the site for a real gym.
