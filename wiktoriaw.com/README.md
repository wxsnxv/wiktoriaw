# wiktoriaw.com

Personal portfolio of **Wiktoria Wiśniewska** — designer & former founder.
Single-page, static, black-and-white editorial. No build step, no dependencies.

## Files

| File | What it is |
|---|---|
| `index.html` | The entire site — self-contained HTML, CSS, JS and an inline SVG locator map |
| `robots.txt` | Allows AI-search crawlers (OAI-SearchBot, GPTBot, PerplexityBot, …) + points to the sitemap |
| `sitemap.xml` | Single-URL sitemap |
| `CNAME` | Custom domain for GitHub Pages |

## Deploy (GitHub Pages)

1. Push this repo to GitHub (see below).
2. **Settings → Pages** → Source: *Deploy from a branch* → `main` / `root`.
3. Custom domain: `wiktoriaw.com` (the `CNAME` file is already here). Add the DNS records GitHub shows you.
4. Tick **Enforce HTTPS**.

## After publishing — GEO / SEO checklist

- [ ] `https://wiktoriaw.com/robots.txt` and `/sitemap.xml` resolve at the domain root.
- [ ] Redirect `www`, `http`, and the old portfolio → `https://wiktoriaw.com` (one canonical URL).
- [ ] Submit the sitemap in **Google Search Console** and **Bing Webmaster Tools**.
- [ ] Add `wiktoriaw.com` to your **LinkedIn** profile — closes the `sameAs` entity loop.

## Editing notes

- **"Currently in Singapore"** status: the `<span class="avail">` in the top bar — edit the text or delete the span.
- **Contact email / LinkedIn**: in the `#contact` section near the bottom.
- **Field notes & projects**: plain HTML inside `index.html`.
- **Structured data**: the `Person` / `ProfilePage` JSON-LD lives in `<head>` — keep it in sync if your title, employer or links change.
