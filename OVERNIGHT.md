# Never Drop A Lead — Overnight ship report

**When:** 2026-09-16 ~02:30 AM ET (America/New_York)  
**For:** Frank Accettulli — morning review  
**Live URL:** https://faccett66.github.io/neverdropalead-preview/

---

## What shipped

Showcase polish on the public soft storefront so **free audit · limited time** is impossible to miss and the page feels finished.

### Free-audit CTAs (everywhere that matters)
- **Nav:** lime primary button — “Free audit · limited time”
- **Hero:** primary CTA + offer chip (mailto with intake prompts)
- **How it works:** Audit step highlighted (Free · limited time) + CTA row
- **Pricing:** Audit card elevated as limited-time free; CTA on every tier + default-quote bar
- **Bottom CTA:** personal tone + free-audit button (not bare email)
- **Sticky bar:** fixed bottom bar appears after scrolling past the hero

### Copy / brand
- Public brand stays **Never Drop A Lead** (CATCH only in an HTML comment; not customer-facing)
- Model **Audit → Install → Watch** reinforced in hero meta, sticky, footer CTA
- Tone: professional excellence; audits cost **mostly personal time, not cash**
- “Our team” → first-person / personal review language
- Preview pill on nav (honest soft storefront; domain not registered tonight)

### Visual consistency
- Dark + lime mark in **nav, favicon, footer** (same `logo-mark-192` / favicon set)
- Footer uses mark + wordmark (matches nav) instead of mismatched lockup crop
- Assets verified live: favicon + logo mark 200 OK

### Links / unfinished surfaces
- No lorem / TODO / placeholder forms on the public page
- All audit CTAs use a single polished mailto to `faccett66@gmail.com`
- Internal ops pages (`catch/ops/pay.html`, intake) left alone — not on Pages

---

## Live URL

**https://faccett66.github.io/neverdropalead-preview/**

Repo: `faccett66/neverdropalead-preview` · branch `main` · GitHub Pages `/`

---

## Deliberately not done (per brief)

| Item | Status |
|---|---|
| Register **neverdropalead.com** | Skipped — Frank said later |
| Stripe live charges / Payment Links | **Needs Frank auth** — `ops/FILL-ME.json` still has `[[FILL: STRIPE_PAYMENT_LINK_*]]`; `ops/STRIPE-SETUP.md` waiting on Stripe dashboard. Did not block storefront. |
| poolparty-preview | Untouched |

---

## Paths

| Role | Path |
|---|---|
| Pages working tree | `/workspace/ndl-public/` |
| Internal ops / brief | `/workspace/catch/` |
| Public HTML mirror | `/workspace/catch/neverdropalead.html` |
| This report | `/workspace/ndl-public/OVERNIGHT.md` (+ copy under catch) |

---

## Morning checklist for Frank

1. Open the live URL on phone + desktop — scroll for sticky bar.
2. Tap **Book free audit** — confirm mailto opens with subject/body.
3. When ready: Stripe Payment Links → paste into `catch/ops/FILL-ME.json` + `pay.html`.
4. Domain registration later — preview stays on GitHub Pages until then.
