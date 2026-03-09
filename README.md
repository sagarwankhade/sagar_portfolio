# Sagar Wankhade Portfolio

Professional static developer portfolio built with plain HTML, CSS, and JavaScript for GitHub Pages.

Live site:
`https://sagarwankhade.github.io/portfolio/`

## Overview

This project is a one-page portfolio website designed to promote freelance software development services.

It includes:

- Hero section with strong service positioning
- Dark/light theme toggle
- Animated typing effect
- Dot grid hero background
- Splash cursor effect
- Services, projects, skills, trust, process, and contact sections
- WhatsApp-first conversion flow
- SEO metadata, structured data, `robots.txt`, and `sitemap.xml`
- GitHub Pages friendly static file structure

## Tech Stack

- HTML
- CSS
- JavaScript

No framework is used, so the site can be hosted directly on GitHub Pages.

## Project Structure

```text
portfolio/
├── index.html
├── style.css
├── script.js
├── favicon.svg
├── robots.txt
├── sitemap.xml
├── google3cbcba2092269dfc.html
├── portfolio/
│   └── index.html
└── images/
    ├── favicon.svg
    ├── profile.jpg
    ├── project-analytics.svg
    ├── project-booking.svg
    ├── project-commerce.svg
    ├── project-crm.svg
    ├── project-erp.svg
    └── project-fintech.svg
```

## Main Files

- `index.html`
  Main page content, SEO tags, structured data, and page sections.

- `style.css`
  Full visual system, responsive layout, animations, glassmorphism styling, hero presentation, and UI components.

- `script.js`
  Theme toggle, mobile navigation, typing effect, reveal animations, animated counters, WhatsApp contact behavior, splash cursor, and hero dot grid.

- `portfolio/index.html`
  Redirect route for `/portfolio/`.

- `robots.txt`
  Search engine crawl instructions.

- `sitemap.xml`
  Sitemap for search indexing.

## Features

- Responsive design for desktop, tablet, and mobile
- SEO-focused title, meta description, keywords, Open Graph, Twitter tags, and JSON-LD
- WhatsApp-first lead generation flow
- Prefilled WhatsApp message links
- Interactive hero effects
- Conversion-focused sections for freelance services

## Local Usage

Open `index.html` directly in a browser, or serve the folder with any static server.

Example with Python:

```bash
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## Deployment

This project is intended for GitHub Pages.

### GitHub Pages Steps

1. Push the repository to GitHub.
2. Open repository `Settings`.
3. Go to `Pages`.
4. Set source to the correct branch, usually `main`.
5. Save the settings.
6. Wait for GitHub Pages deployment.

Live path used in SEO settings:

`https://sagarwankhade.github.io/portfolio/`

## Customization

### Update personal details

Edit `index.html` for:

- Name
- Role
- WhatsApp number
- LinkedIn URL
- Contact text
- Project content
- SEO copy

### Update hero typing text

Edit the `phrases` array in `script.js`.

### Update WhatsApp message text

Search for:

`https://wa.me/918554068494`

in `index.html` and `script.js`.

### Update profile image

Replace:

`images/profile.jpg`

### Update favicon

Replace:

- `favicon.svg`
- `images/favicon.svg`

## SEO Notes

SEO setup currently includes:

- Page title
- Meta description
- Meta keywords
- Open Graph tags
- Twitter card tags
- Canonical URL
- JSON-LD `Person` schema
- `robots.txt`
- `sitemap.xml`
- Google verification file

If the site URL changes, update:

- `index.html`
- `robots.txt`
- `sitemap.xml`

## Contact Flow

The site is optimized for WhatsApp-based freelance inquiries.

Visible actions route users to WhatsApp with prefilled text for:

- General project inquiry
- Quick chat
- Quote request
- Consultation request
- Contact form submission

## Notes

- The contact form does not submit to a backend.
- It redirects users to WhatsApp with their entered message.
- Some project links still use placeholder GitHub/demo URLs and should be replaced with real links.

## License

Personal portfolio project for Sagar Wankhade.
