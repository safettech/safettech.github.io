# Safe-T TECH International — Website

Static website for Safe-T TECH International (Sialkot, Pakistan), ready to deploy on GitHub Pages at https://safettech.github.io/. Plain HTML/CSS with one shared stylesheet and a small inline script on the contact page — **no build step**: upload the contents of this folder as-is.

## Structure

| File | Purpose |
|---|---|
| `index.html` | Home — "Clothing Manufacturer in Pakistan", all five divisions, process, portfolio/catalogue links |
| `sports-teamwear.html` | Division 1 — sportswear & custom teamwear (football, American football, basketball, baseball, cricket) |
| `womens-fashion.html` | Division 2 — women's fashion, athleisure, private label swimwear & crystal stage bikinis |
| `streetwear-outerwear.html` | Division 3 — leather jackets, varsity jackets, heavyweight hoodies, streetwear |
| `uniforms-workwear.html` | Division 4 — uniforms & protective workwear (medical, firefighter, industrial, all fields) |
| `inspection-services.html` | Division 5 — third-party inspection services (IPI, DUPRO, PSI/FRI, CLS, Factory Audit) |
| `contact.html` | Quote/sample form that composes a prefilled WhatsApp message (no backend), plus contact cards |
| `style.css` | Shared stylesheet — navy `#25235c` / gold `#e8b84b` brand theme, responsive |
| `assets/` | Logo (`logo.png`, shield on navy — never place on a white background) and product images (all clean, unbranded, each < 400 KB) |
| `robots.txt` | Crawler rules + sitemap pointer |
| `sitemap.xml` | All 7 pages with https://safettech.github.io/ URLs |

## Notes

- Every page has a keyword-led `<title>`, meta description, canonical URL and Open Graph tags (per the SEO keyword brief of 2026-10-26).
- No prices appear anywhere on the site; all CTAs route to WhatsApp (+92-339-5099397) or the contact form.
- Portfolio/catalogue buttons link to the Google Drive files/folders (Safe-T TECH Portfolios / Catalogues).
- Deploy: create a GitHub account/repo named `safettech.github.io` (or a `safettech` org/user pages repo), push this folder's contents to the publishing branch, and enable Pages. After going live, submit `sitemap.xml` in Google Search Console.
