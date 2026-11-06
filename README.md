# DiDo84 — management consultancy & participations

Static marketing site (HTML / CSS / JS, no build step) hosted on GitHub Pages
at `dido84.shop`.

> Generated from `C:\Users\souha\coaching-sites-factory` (content file `sites/dido84.mjs`).
> To change the content, edit that file and run `node build.mjs dido84` — editing the
> HTML here directly would be overwritten on the next build.

## Before you promote this site

| Priority | What | Where |
|---|---|---|
| 🔴 Blocking | Legal page: fill every `[BRACKET]` (legal name, address, state, payment provider). Have a lawyer review it if you can. | `legal.html` |
| 🟠 Important | `contact@dido84.shop` doesn't exist yet: set up free email forwarding in Namecheap (*Domain List → Manage → Redirect Email*). | Namecheap |
| 🟠 Important | Contact form: replace `VOTRE_ID_FORMSPREE` with your Formspree id (until then it falls back to `mailto:`). | `contact.html` |
| 🟠 Important | Add a real introduction of the coach (name, background, photo). Never invent credentials. | `about.html` |
| 🟡 Later | Prices ($Quote / $Quote / $Declined) and plan contents should match what you actually sell. | `index.html` `#pricing` |
| 🟡 Later | Testimonials: only add real ones, with permission. Fake reviews are illegal (FTC). | — |

## Business description (Stripe, directories…)

```
We are DiDo84, a management consultancy and holding company based in Berchem in Antwerp, filing accounts since 2006. Much of our work starts with a set of published annual accounts, and the most valuable thing we can put on this page is what those accounts do not prove. A small Belgian company files an abridged or micro schema, which does not require turnover to be disclosed at all, so the revenue line on every public database sits empty. A small company has no statutory auditor, so the figures were prepared by the company and filed, not verified by anyone. Filing is a publicity formality, and the deadline runs to seven months after year end, meaning the document on the register is the latest public picture for a further year. Equity is not cash, and reading it as though it were is the most common mistake made with these documents. What the filings genuinely show is the pattern: whether a company filed, on time, consistently. We say all of this about our own filings as readily as about anyone else's. Site: dido84.shop
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
