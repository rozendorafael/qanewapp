# Teya — New App · QA Bug Report

## Meta
- Presenter (for questions): Rafael Rozendo
- Build tested: v2.4.0 (build 1284) — PLACEHOLDER, user to confirm
- Audience: Eng + Product/PM
- Language: English
- Tone: corporate clean, light, professional
- Severity scale: Blocker / Major / Minor / Trivial
- Media per bug: print (image-slot, user fills) + video reference (slot + link)

## System
- Fonts: "Space Grotesk" (display/headings) + "IBM Plex Sans" (body) + "IBM Plex Mono" (IDs, build no., device, code-ish meta)
- Palette: light. bg #F6F7F9, surface #FFFFFF, ink #15191F, muted #5A6472, hairline #E4E7EC
- Accent (deck chrome): teal-green #137A53 (tweakable)
- Severity colors: Blocker #DC2626 · Major #E8870B · Minor #2563EB · Trivial #6B7280

## Type scale (1920x1080)
--type-display 84 / --type-title 60 / --type-subtitle 40 / --type-body 30 / --type-small 24 / --type-mono 22
pad-x 110 / pad-top 96 / pad-bottom 80

## Slide sequence (titles)
1. Cover — "QA Bug Report" + Teya New App, presenter, build, date
2. Summary — counts by severity, total, severity bars (the visual summary)
3. Severity scale — define Blocker/Major/Minor/Trivial + how to read a bug slide
4. Bug 01 — Card reader drops connection mid-payment [Blocker]
5. Bug 02 — Transaction history fails to refresh [Major]
6. Bug 03 — Receipt totals show wrong currency format [Major]
7. Bug 04 — Email verification is skipped during onboarding [Major]
8. Bug 05 — Dashboard chart labels overlap on small screens [Minor]
9. Bug 06 — Settings toggle label is misaligned [Trivial]
10. Priorities & next steps — table: bug / severity / suggested action
11. Questions — contact (Rafael Rozendo)

## Bug slide layout
- Left ~54%: large screenshot slot (image-slot) + below, a video-reference row (small thumb slot w/ play overlay + editable link)
- Right ~46%: severity badge, Bug ID + title, description, fields:
  Steps to reproduce (2-3) · Expected vs Actual · meta row (Device/OS · Screen/module)

## Severity counts (placeholder content)
Blocker 1 · Major 3 · Minor 1 · Trivial 1 · Total 6
