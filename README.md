# Bams Fencing — Demo Website

Single-page demo site for **Bams Fencing**, a custom wood, vinyl & aluminum fence
contractor in Bradenton, FL (4.6★ on Google, 74 reviews). Fences built from scratch
with commercial-grade lumber (not prefab panels), custom gates, and fence repair /
restoration across Bradenton and all of Manatee County.

- **Live demo:** https://wilsoninnovations.net/bams-fencing/
- **Phone:** (941) 518-0500 (tel: and sms: CTAs)
- **Address:** 1212 59th Avenue East, Bradenton, FL 34203
- **Hours:** Mon–Thu 8 AM – 5 PM, Fri 8 AM – 4:30 PM, Sat 8 AM – 12 PM, Sun closed (per Google listing)
- **Tier:** 1 — Clean Slate (per wave manifest)

## Design

- **Fonts:** Combo (display, casual slab) + Noto Sans Display (body sans) — pre-assigned in manifest
- **Palette:** forest green (#2f5233 / #1d3421) + cedar brown (#a35a2e / #7d4220)
  + warm off-white (#f5efe3 / #faf5ea)
- Self-contained `index.html` — inline CSS + vanilla JS, works from `file://`.
- Full Tier-1 "Clean Slate" system per DESIGN.md: airy Combo headline with cedar
  emphasis words, above-the-fold hero stack (eyebrow → headline → sub → CTA pair →
  glass trust chip), verified visible with no scroll at 1440×900, 1366×768 and 390px;
  slow Ken Burns hero photo, one-shot blur/scale scroll reveals (IntersectionObserver,
  rootMargin bottom +12%, momentum-scroll sweep), layered soft shadows, hover lifts,
  sheen-sweep primary CTA — all gated behind `prefers-reduced-motion`. FenceContractor
  JSON-LD with aggregateRating (4.6 / 74) and opening hours.
- **Mobile header standard:** call CTA flush right at all widths; icon-only ≤600px;
  brand wraps to 2 lines, never clipped. **No fixed/sticky bottom mobile call bar** (banned).

## Images (Unsplash — self-hosted in assets/, PIL re-encoded ≤350KB)

Record of Unsplash photo IDs used (for cross-wave dedup — READMEs must carry
self-hosted IDs). Global dedup grep run against websites/*/index.html + websites/*/README.md
+ templates/* immediately before download; every ID below was globally absent and HTTP-200 verified.

- `assets/hero.jpg` (+ og:image) — photo-1759502141256-45d54807853b (clean horizontal-slat fence lined with tall evergreens)
- `assets/wood.jpg` — photo-1593285247650-cd7bb44adcfd (warm natural cedar wood board fence with grass)
- `assets/vinyl.jpg` — photo-1562095633-e1c63438378a (crisp white vinyl/picket fence curving along a green field, houses beyond)
- `assets/aluminum.jpg` — photo-1587780843696-044a14ea63ae (black ornamental spear-top aluminum fence)
- `assets/repair.jpg` — photo-1692740278522-3615f694fbe0 (weathered wood fence overgrown with vines — repair/restoration)
- `assets/area.jpg` — photo-1613756178402-ed5c1ea492b4 (warm cedar dog-ear privacy fence with a home behind it)

## Notes

- `noindex` meta is present while this is a demo — remove when the site goes live.
- Photography is Unsplash placeholder stock; swap in real job photos after the sale.
- Review excerpts are real Google reviews of the business (first name + last initial;
  owner named Thomas / "Tom"). Aggregate 4.6 / 74 shown (≥4.4).
- No invented facts: no license number, founding year, or email (none available).
  Aluminum fencing is included (in the business's own category: Vinyl, Wood & Aluminum);
  HOA-documentation help and Saturday quotes are drawn directly from reviews.

Website by [Wilson Innovations](https://wilsoninnovations.net)
