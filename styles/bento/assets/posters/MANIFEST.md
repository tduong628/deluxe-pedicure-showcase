# Pedicure Poster Manifest — Deluxe Nail Spa Kiosk Display

Generated 2026-09-06 via ChatGPT desktop MCP (`mcp__chatgpt-desktop__generate_image`), matching the visual quality/layout language of the reference flyer at `/Volumes/Claude/John/Social Marketing/Fall_Winter_Pedicure_2026/deluxe_fall_winter_pedicure_flyer.png`. Each poster is a single, fully-designed graphic (wordmark, headline, hero photo, circular price seal, benefit cards, numbered ritual steps, footer bar, botanical corner illustrations) — no code/CSS assembly needed, this image IS the final slide.

Every file below was personally proofread by Lens, character-by-character, against the real content in its source `slide-*.html` file. One text error was found and corrected (see Romantic Rose, attempt 2). All other posters passed proofreading on the first generation attempt.

---

### 1. `poster-ocean-breeze.png`
- **Source:** `slide-01-ocean-breeze.html`
- **Name shown:** Ocean Breeze Pedicure
- **Price shown:** From $55 · Signature Service
- **Proofread:** PASS (attempt 1) — wordmark, badge ("Signature Pedicure · Deluxe House"), tagline, promise ("Brighten. Detox. Renew."), both benefit cards (Pearl Powder Power / Seaweed Detox), all 4 ritual steps (Pearl Soak → Hydrating Scrub → Seaweed Wrap with Nourishing Mask → Pearl Massage Cream), and footer all verified verbatim against source.

### 2. `poster-honey-orange.png`
- **Source:** `slide-03-honey-orange.html`
- **Name shown:** Honey Orange Zest Spa Pedicure
- **Price shown:** From $55
- **Proofread:** PASS (attempt 1) — badge ("Signature Pedicure · Year Round"), all 3 benefit cards (Vitamin C Glow / Honey Hydration / Orange Revitalization), all 5 included steps (Sea Salt Soak, Honey Sugar Scrub, Mud Masque, Massage Lotion, Real Orange Slices), footer ("Ready When You Are · Ask At The Front Desk") verified verbatim.

### 3. `poster-herbal.png`
- **Source:** `slide-04-zen-herbal.html`
- **Name shown:** Herbal Spa Pedicure Experience
- **Price shown:** From $85 · Signature Service
- **Proofread:** PASS (attempt 1) — dense poster with 3 benefit cards, 3 botanical-blend cards, and a 5-step "75-Minute Treatment" ritual, all verified verbatim including "Renuspa" and the full Eucalyptus · Lavender · Chamomile · Green Tea line.

### 4. `poster-romantic-rose.png`
- **Source:** `slide-05-romantic-rose.html`
- **Name shown:** Romantic Rose Pedicure
- **Price shown:** From $75
- **Proofread:** FAIL then PASS (2 attempts) — attempt 1 had a typo, "collagen hydiation" instead of "collagen hydration." Regenerated with an explicit spelling callout; attempt 2 confirmed "collagen hydration" spelled correctly, plus all 3 info items, 4 included steps, 3 add-on pills, script line, and footer verified verbatim.

### 5. `poster-lavender.png`
- **Source:** `slide-06-lavender-spa.html`
- **Name shown:** Lavender Spa Pedicure
- **Price shown:** From $45
- **Proofread:** PASS (attempt 1) — badge ("Aromatherapy Pedicure · Deluxe House"), all 3 benefit items (Natural Anxiety Relief / Anti-Inflammatory Care / Skin Restoration), all 4 included steps, script line, and footer verified verbatim.

### 6. `poster-basic-spa.png`
- **Source:** `slide-07-basic-spa.html` (date-aware pricing — verified `currentPrice()` logic: cutover is June 1, 2026; today is 2026-09-06, which is past cutover, so price resolves to **$38 with no note**, exactly as generated)
- **Name shown:** Basic Spa Pedicure
- **Price shown:** From $38 (no additional note — confirmed correct for today's date)
- **Proofread:** PASS (attempt 1) — badge ("Essential Pedicure · Everyday Care"), both benefit items, all 4 included steps, disclaimer line ("Callus treatment is not included — but we're happy to add it for you. Just ask."), and footer verified verbatim. Price digits confirmed as exactly "38."

### 7. `poster-pearl-steam.png`
- **Source:** `slide-08-pearl-steam.html`
- **Name shown:** The Pearl & Steam Experience
- **Price shown:** From $65
- **Proofread:** PASS (attempt 1) — the 8-step ritual (more steps than any other pedicure) laid out cleanly as two rows of four: Pearl Mineral Soak, Sugar Scrub, Micro-Exfoliation Scrub, Nourishing Foot Mask, Moisturizing Lotion, Paraffin Wax, Steam Therapy, 10-Minute Massage — all 8 titles verified verbatim, plus all 4 "Why You'll Love It" benefit items and footer.

### 8. `poster-green-tea.png`
- **Source:** `slide-09-green-tea.html`
- **Name shown:** Green Tea Pedicure
- **Price shown:** From $45
- **Proofread:** PASS (attempt 1) — all 3 benefit items (Anti-Aging / Deep Detox / Aromatherapy), all 4 ritual steps with body copy, and the full-caps footer ("DELUXE NAIL SPA · ANTIOXIDANT PEDICURE · CARY, NC") verified verbatim.

### 9. `poster-collagen.png`
- **Source:** `slide-10-collagen-spa.html`
- **Name shown:** Collagen Spa Experience
- **Price shown:** From $85
- **Proofread:** PASS (attempt 1) — both the 5-step ritual (Collagen Crystal Soak → Sugar Cane Scrub → Collagen Cream Mask → Muscle-Relaxing Gel → Collagen Massage Lotion) AND the separate 4-item "Also Included" row (Steam Therapy, Collagen Socks, Cooling Gel Finish, 10-Min Hot Stone Massage) fit cleanly as two distinct panels; all 5 "Why You'll Love It" bullet points also verified verbatim.

---

## Vietnamese flag check
No Vietnamese flag or any flag imagery appears in any of the 9 posters — not applicable to this batch.

## Notes for Quill / Victor / posting pipeline
- All 9 files are complete, finished graphic-design slides (photo + baked-in text) — ready to drop directly into the kiosk slideshow rotation, no further code/CSS work needed.
- File paths are absolute and live in `Images`-equivalent asset location for this project: `/Volumes/Claude/John/Slideshow-Deluxe/styles/bento/assets/posters/`.
- These replace the coded HTML bento-box versions (`slide-01` through `slide-10` in the parent `bento/` folder) as the visual source of truth for these 9 pedicures; the HTML files still hold the authoritative pricing/copy data and should remain as the content source of truth even though the display itself now uses these PNGs.
