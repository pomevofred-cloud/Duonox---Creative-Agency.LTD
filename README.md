# Duonox – Creative Agency

Source files for the Duonox Creative Agency website — a static site (HTML, images, and configuration) served from the `public_html` web root.

## Structure

| File | Purpose |
|------|---------|
| `index.html` | Homepage |
| `services.html` | Services page |
| `pricing.html` | Pricing page |
| `contact.html` | Contact page |
| `privacy-policy.html` / `privacy-policy-mobile.html` | Privacy policy |
| `404.html` | Custom not-found page |
| `.htaccess` | Apache server configuration (redirects, headers) |
| `robots.txt` / `sitemap.xml` | Search engine crawling & indexing |
| `site.webmanifest` | Progressive Web App manifest |
| `favicon.*`, `icon-*.png`, `apple-touch-icon.png` | Site icons |
| `og-image.jpg` | Open Graph / social share image |
| `google*.html` | Google Search Console verification |

## Deployment

The site is static — upload the contents of the repository to the web server's
`public_html` (or equivalent) document root. No build step is required.

## Managing updates

This repository tracks all changes to the website. To make an update:

1. Edit the relevant file(s).
2. Commit the change with a clear message.
3. Push to GitHub and deploy the updated files to the server.
