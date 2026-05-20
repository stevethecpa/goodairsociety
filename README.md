# The Good Air Society — Website

Static website for [The Good Air Society](https://goodairsociety.org), a non-profit society in formation in Chilliwack, BC, for men 25–45 who want to be outside, get stronger together, and build lasting friendships.

## Files

| File | Purpose |
|------|---------|
| `index.html` | Landing page — hero, mission/vision, problem stats, three program pillars, sample week, values, founder note, FAQ |
| `contact.html` | Contact page — direct email contact + placeholder for launch-list Typeform |
| `steven_headshot_square.jpg` | Founder portrait used on the landing page (480×480) |
| `steven_headshot_thumb.jpg` | Smaller variant (240×240) |
| `steven_headshot2.jpg` | Master source image |

## Deployment

The site is intended to be served by **Cloudflare Pages**, auto-deploying from the `main` branch of this repository. Custom domain: `goodairsociety.org` (and `www.goodairsociety.org`).

Email routing for `info@goodairsociety.org` and `steven@goodairsociety.org` is handled by Cloudflare Email Routing, forwarding to a dedicated Society Gmail.

## Editing

This is a hand-written static site — no build step, no framework, no dependencies. Edit the HTML files directly. Commit and push; Cloudflare Pages will deploy the change within ~30 seconds.

The Typeform placeholder in `contact.html` is marked with an HTML comment (`TYPEFORM EMBED PLACEHOLDER`); replace the `.typeform-placeholder` block with the Typeform embed code when the form is ready.

## Brand

- **Name**: The Good Air Society
- **Tagline**: Good air. Hard miles. Real friends.
- **Primary colour**: ember / warm amber `#d97a3a`
- **Background**: cream / mist `#f5f1ea`
- **Ink**: dark slate `#1f2a30`
- **Typography**: Fraunces (serif, headings) + Inter (sans, body), both from Google Fonts

## Contact

`info@goodairsociety.org`
