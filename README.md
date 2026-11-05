# JJ Pathfinder — website preview

Redesign of the live jjpathfinder.com — video editing & social media agency.
Founder: Ahtesham Shahid, Haroonabad, Punjab, Pakistan.
Contact: +92 303 777 9335, contact@jjpathfinder.com.

## Source

Stitch export supplied by Dad as a zip on 2026-11-05
(`stitch_jj_pathfinder_3d_redesign_0_1ue5.zip`).
The 4 production pages were copied unchanged except for the file rename
(`code.html` -> page name). The case-study page was missing from the
production set, so it was taken from the matching Stitch variant
(`jj_pathfinder_case_study_with_audio_telemetry_harmonic_chimes`).

## Pages

- `index.html` — Home: "We Turn Raw Footage Into Viral Authority", 2-slot
  countdown, FAQ search
- `work.html` — Work Vault / portfolio
- `services.html` — Services & pricing: $1,850 / $3,400 / $5,900 per month
- `case-study.html` — Retention breakdown with audio telemetry chimes
- `onboarding.html` — Client scope inquiry form

## Deploy (Render static site)

- Publish directory: `.` (repo root)
- Build command: none (static HTML, Tailwind via CDN, Google Fonts)
- No backend, no secrets, no build step.

## Fixes applied 2026-11-05 (second-AI review)

- `case-study.html`: fake testimonial removed (invented name, $1.4M claim,
  AI photo, "VERIFIED" badge) — replaced with a clearly-marked placeholder.
  Logo now links back to Home; dead Client Portal / Privacy / Terms links
  removed; "VERIFIED" removed from the pipeline-gain metric.
- `onboarding.html`: form no longer pretends to send — the alert now says
  it is a demo and points to WhatsApp. Inputs got `name` attributes.
  Reply time corrected to 24–48h (matches the live site).
- `index.html`: FAQ search no longer crashes on `(`, `*`, `[` etc.
  Footer email corrected to contact@jjpathfinder.com (live site address).
  Copyright 2025 → 2026.

## Known preview notes — confirm before the real domain goes live

- Prices ($1,850 / $3,400 / $5,900) come from the Stitch draft, not from
  Ahtesham. Confirm them before pointing jjpathfinder.com here.
- All big numbers are Stitch inventions, not verified: 299M+ views,
  318% / 68.4% retention, $1.4M pipeline, 92.4% retention, +140K
  subscribers. The live site's real stats (300+ brands, 190+ countries,
  5+ years, 1300+ projects) were dropped from this design — restore or
  confirm real numbers with Ahtesham.
- `work.html` uses grey placeholder thumbnails, not real project videos.
  Its filter buttons do nothing and it claims 48 items but shows 3.
- The onboarding form is a demo: it shows an alert, it does not send
  anything anywhere. A real form backend is still needed.
- The founder portrait in `case-study.html` is AI-generated, not a real
  photo. Real photo needed before the client sees it.
- Mobile nav: `index.html` and `case-study.html` have no hamburger — on a
  phone there is no navigation at all.
- The homepage countdown says "Q1" intake with 2 slots — it is November
  (Q4) and the timer runs to zero while still showing slots available.
- The Stitch manifest over-promises (showreel player, playable video
  modals, 4-step onboarding flow) — none of those exist in these files.
- Design: "Cybernetic Cinema" — dark #07090E, neon cyan #00F2FE.
