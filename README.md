# Tayar Accounting — tayar accounting & financial services llc

Static marketing site (HTML / CSS / JS, no build step) hosted on GitHub Pages
at `tayaraccountingandfinancialservicesllc.shop`.

> Generated from `C:\Users\souha\coaching-sites-factory` (content file `sites/tayaraccountingandfinancialservicesllc.mjs`).
> To change the content, edit that file and run `node build.mjs tayaraccountingandfinancialservicesllc` — editing the
> HTML here directly would be overwritten on the next build.

## Before you promote this site

| Priority | What | Where |
|---|---|---|
| 🔴 Blocking | Legal page: fill every `[BRACKET]` (legal name, address, state, payment provider). Have a lawyer review it if you can. | `legal.html` |
| 🟠 Important | `contact@tayaraccountingandfinancialservicesllc.shop` doesn't exist yet: set up free email forwarding in Namecheap (*Domain List → Manage → Redirect Email*). | Namecheap |
| 🟠 Important | Contact form: replace `VOTRE_ID_FORMSPREE` with your Formspree id (until then it falls back to `mailto:`). | `contact.html` |
| 🟠 Important | Add a real introduction of the coach (name, background, photo). Never invent credentials. | `about.html` |
| 🟡 Later | Prices ($Quote / $Quote / $Quote) and plan contents should match what you actually sell. | `index.html` `#pricing` |
| 🟡 Later | Testimonials: only add real ones, with permission. Fake reviews are illegal (FTC). | — |

## Business description (Stripe, directories…)

```
Tayar Accounting & Financial Services LLC, a Florida limited liability company (document number L06000059102) trading since 2006, provides accounting and tax services to established businesses: preparation of business tax returns for partnerships, S corporations and corporations, annual financial statements prepared from the company's records, payroll and compliance filing across the year, and management reporting with a yearly planning review. Engagements are set out in a written letter stating scope and fees before work begins. The company is not a certified public accounting firm and performs no audit, review or attest engagement. Site: tayaraccountingandfinancialservicesllc.shop
```

## Structure

```
index.html            Home: hero, programs, method, pricing, approach, FAQ
programs.html         The four programs in detail
about.html            How we work, principles
contact.html          Contact form
legal.html            Business info, privacy policy, terms of service
404.html              Error page (absolute paths)
assets/css/style.css  Brand colors at the top, shared styles below
assets/js/main.js     Menu, theme, animations, form
```

## DNS (Namecheap → Advanced DNS)

Delete the parking records, then add:

| Type | Host | Value |
|---|---|---|
| A Record | `@` | `185.199.108.153` |
| A Record | `@` | `185.199.109.153` |
| A Record | `@` | `185.199.110.153` |
| A Record | `@` | `185.199.111.153` |
| CNAME Record | `www` | `hamzaniceguy99-glitch.github.io.` |
