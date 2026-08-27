# naama-bar-shira

The official website of Israeli fantasy author **Naama Bar Shira** — writing in English as **N.B. Shira**.

Winner of the Geffen Award (2024), Book of the Year from Real Book Recommendations (2026),
and the Kipod Award for cover design (2025). Nine published novels, with the first now in English.

## What this is

A single self-contained `index.html`. No build step, no dependencies, no external requests
except Google Fonts — every image is embedded in the file. Drop it on any static host and it works.

- Bilingual Hebrew / English with full RTL–LTR switching
- The books grouped by world, with a reading-order guide
- A map of the real settings, from Crusader Tyre to the Dead Sea
- A character gallery
- Direct ordering: the cart composes a WhatsApp order to the author

## Editing

Everything you are likely to change sits at the top of the `<script>` block:

- `PHONE`, `PHONE_DISP`, `BIT_PHONE` — where orders and enquiries go
- `LINKS` — the readers' WhatsApp group, Instagram, TikTok, Facebook
- `BOOKS` — titles, prices, accolades
- `PLACES` — map settings, by latitude and longitude
- `GALLERY` — the cast

## Deployment

Served by GitHub Pages from the `main` branch.
