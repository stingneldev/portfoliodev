# Product

<!-- impeccable:product-schema 1 -->

## Platform

web

## Users

Owners of small businesses who need a website, landing page, or online store and are deciding whether to hire Arthur Stingnel, a freelance web developer. They arrive from a referral or a link, size up whether Arthur is credible and easy to work with, and want to reach out directly (WhatsApp, e-mail, LinkedIn) without a formal process.

## Product Purpose

A one-page personal portfolio and lead-generation site for Arthur Stingnel, a web developer in Colatina, ES, Brazil, with 2+ years of experience and a student at IFES (Sistemas de Informação). It shows what Arthur builds, proves it with real projects, and turns a visitor into a conversation. Success is a business owner contacting Arthur about a project.

## Positioning

Arthur works with clear communication, no technical jargon and no runaround, and builds sites focused on conversion, speed, and SEO. Both claims are confirmed by Arthur.

## Operating Context

Single static page, in Brazilian Portuguese (pt-BR). Primary action is contact, with WhatsApp as the lead channel, then e-mail and LinkedIn. Visitors typically land on it from a shared link or from a project Arthur delivered.

## Capabilities and Constraints

- Services offered: landing pages, institutional sites, e-commerce, responsive design, performance and SEO, maintenance and support.
- Delivered as a single HTML file with inline CSS and JS plus local assets in `assets/`; the animation library (anime.js) is vendored locally, with no CDN or runtime external dependency.
- Copy lives in `Copy.txt` and the visual rules in `Design System.txt`; the page's wording is the source of truth and was not to be reworded when first built.
- The headline numbers on the page (+20 projects delivered, 100% client satisfaction, 2+ years) were provided by Arthur.

## Brand Commitments

- Name shown as "Arthur Stingnel" (surname "Sousa" deliberately dropped from visible text); logo is "AS.".
- Arthur asked for a palette change and allowed the design system to change: a deep navy base (#0A192F family, dark and closed rather than bright blue) balanced with a warm sand tone, in a light and a dark theme (user toggle plus system preference), ice-white accent in the dark theme (no color accent; emphasis comes from contrast) and deep navy in the light theme, reserved for calls to action and key icons. `Design System.txt` predates this and is out of date on color.
- Type pairing now: Sora for headings, Manrope for text, JetBrains Mono for code and labels, Playfair Display Italic for one emphasized word per title.

## Evidence on Hand

- Two real projects: Beiço de Pulga (institutional site for an award-winning craft brewery, 2025, https://beico-de-pulga.vercel.app/) and Dengo Pet Shop (landing page for a pet shop, 2026, https://dengo-petshop.vercel.app/).
- A professional profile photo (`assets/profile.jpg`) and the headline numbers above.
- No client testimonials, case-study metrics, or client logos exist yet; none may be invented.

## Product Principles

1. Contact is the point: every section should make reaching Arthur easier, not decorate.
2. Credible over flashy: real projects and plain language outweigh effects.
3. Speak to business owners, not developers: no jargon.
4. Show the craft Arthur sells: the site itself must be fast, responsive, and conversion-minded.
5. Never fabricate proof: only claims and evidence Arthur can stand behind.

## Accessibility & Inclusion

Targets WCAG AA contrast, full keyboard navigation, touch targets of at least 44px, and semantic HTML with alt text. Motion must respect `prefers-reduced-motion`.
