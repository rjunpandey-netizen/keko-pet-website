# KeKo Pet — Website (Starter Build)

Static HTML/CSS site built from `KeKo_Pet_Website_Content.docx`. No build step required — plain HTML, one shared stylesheet, works as-is on GitHub Pages, Netlify, or any static host.

## Pages included
- `index.html` — Homepage
- `about.html` — Our Story
- `shop.html` — Shop by category (Chews, Enrichment, Dental, Supplements — Coming Soon)
- `product-himalayan-chew.html` — Full product detail template (hero chew)
- `blog.html` — Blog listing (3 launch articles as stubs)
- `contact.html` — Contact / wholesale enquiry form (static — needs a form handler, see below)

## Deploying via GitHub Pages (free, ~10 minutes)

1. Create a new **public** repository on GitHub, e.g. `keko-pet-website`.
2. Upload this whole folder (or `git init`, `git add .`, `git commit -m "Initial site"`, `git push`).
3. In the repo: **Settings → Pages → Branch: main → /(root) → Save**.
4. GitHub gives you a URL like `https://<username>.github.io/keko-pet-website/` within a few minutes.
5. To use `kekopet.com.au`: in the same Pages settings, add the custom domain, then at VentraIP add a `CNAME` record pointing `www` to `<username>.github.io` and an `A` record for the root domain to GitHub's IPs (GitHub's Pages docs list the current IPs — search "GitHub Pages custom domain A record").

## Before this goes live
- **Photography**: every product image is a placeholder panel. Replace with real product photography (kraft paper / cream background per brand direction) before launch.
- **Email capture**: the newsletter and contact forms currently just show an alert. Wire the newsletter form to Klaviyo's embed/API, and the contact form to Klaviyo, Formspree, or a Shopify contact form once you're on Shopify.
- **Nutritional panel**: `product-himalayan-chew.html` has a placeholder for the Eurofins/ALS panel — swap in once available.
- **This is a marketing/content shell, not a checkout.** Given the plan to launch on Shopify, treat this GitHub build as either (a) a coming-soon/pre-launch site to sit at kekopet.com.au before Shopify goes live, or (b) a content and copy reference to paste into Shopify's theme editor page-by-page.

## Design system
Colours, type, and the topographic-line motif are defined at the top of `css/styles.css` — change the CSS variables there to retheme every page at once.
