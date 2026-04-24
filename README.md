# Sacred Jannah — Shopify Page Template

A complete, fully-editable Shopify page template for the 5 Day Eid Regenesis retreat.
All text, colors, images, links, pillars, services, included items, marquee text, and pricing are editable from the Theme Editor (Customize) in your Shopify admin — no code editing required after install.

---

## What's in this folder

```
shopify-export/
├── sections/
│   └── sacred-jannah.liquid          ← The main section (design + schema)
├── templates/
│   └── page.sacred-jannah.json       ← The page template that loads the section
└── README.md                         ← This file
```

You will also need the AI-generated background video file:
- `bali-beach-waves-woman.mp4` (≈40 MB) — see Step 3 below.

---

## Installation (5 steps)

### Step 1 — Open your Shopify theme code editor

1. In Shopify admin, go to **Online Store → Themes**.
2. On your live theme (or a duplicate, recommended), click **... → Edit code**.

### Step 2 — Add the section file

1. In the left sidebar, expand the **Sections** folder.
2. Click **Add a new section**.
3. Name it exactly: `sacred-jannah` (Shopify will create `sacred-jannah.liquid`).
4. **Delete everything** in the new file.
5. Open `shopify-export/sections/sacred-jannah.liquid` from this export, copy the entire contents, and paste into the new section file.
6. Click **Save**.

### Step 3 — Add the page template

1. In the left sidebar, expand the **Templates** folder.
2. Click **Add a new template**.
3. Set:
   - **Template type:** `page`
   - **Template name:** `sacred-jannah`
   - **File type:** `json`
4. Click **Done**.
5. **Delete everything** in the new template file.
6. Open `shopify-export/templates/page.sacred-jannah.json` from this export, copy the entire contents, and paste into the new template file.
7. Click **Save**.

### Step 4 — Upload the background video

1. In Shopify admin, go to **Settings → Files**.
2. Click **Upload files** and select `bali-beach-waves-woman.mp4`.
3. After upload, click the file and copy its public URL (it will look like `https://cdn.shopify.com/s/files/...`).
4. Save this URL — you'll paste it in the Theme Editor in Step 5.

### Step 5 — Create the page and customize

1. In Shopify admin, go to **Online Store → Pages**.
2. Click **Add page**.
3. Title: e.g. *Sacred Jannah Retreat*.
4. On the right, under **Theme template**, select **sacred-jannah** from the dropdown.
5. Click **Save**.
6. Click **View page** → then click **Customize** in the top admin bar (or go to Themes → Customize → navigate to the page).
7. In the Customize sidebar, click the **Sacred Jannah Retreat** section.
8. Find the **Three Pillars Section** group → paste the video URL from Step 4 into **Background video URL**.
9. Optionally upload your own images in the **Hero**, **Location**, and **Pillars Section** image pickers.
10. Edit any text, colors, pricing links, or add/remove pillars/services/marquee items from the sidebar.
11. Click **Save**.

Your page is live.

---

## What you can edit from the Customize sidebar

**Brand**
- Brand eyebrow & name (logo text)
- Reserve button text & link

**Color Palette**
- Gold (primary), Gold light, Off-white, Dark, Muted, Section alt — all 6 theme colors

**Hero Section**
- Date label, two-line title, keywords, CTA text, hero image

**Spiritual Affirmation**
- Main quote, supporting paragraph, three symbol pillars

**Three Pillars Section**
- Eyebrow, two-line title, background video URL, fallback image
- Each pillar: subtitle, title, description, custom SVG icon

**Location Section**
- Eyebrow, two-line title, description, image

**Services / Modalities**
- Eyebrow, two-line title
- Each service block: tag, title, description

**Marquee**
- Add/remove/reorder scrolling text items

**What's Included & Pricing**
- Eyebrow, two-line title, pricing eyebrow
- Pay-in-full button text + PayPal link
- Installments button text + PayPal link
- Add/remove "included" chips

**Footer**
- Tagline, copyright

---

## Notes & Tips

- **Adding more pillars / services / items:** In Customize, scroll to the bottom of the section and click **Add block** → choose the type.
- **Reordering blocks:** Drag the block handle in the sidebar.
- **Removing the video:** Leave the **Background video URL** field empty — the fallback image will be used.
- **Performance:** The video is ~40 MB. Shopify's CDN handles it well, but for slow connections consider adding a poster image.
- **Mobile:** The grid sections collapse to single column under 768px wide.
- **Fonts:** Cinzel + PT Serif are loaded from Google Fonts. If your theme already loads them, no conflict.

---

## Customizing further

If you want to add a contact form, related products, or hook this into a Shopify product (so people pay through Shopify checkout instead of PayPal), let me know — I can extend the section to support a product picker and Shopify's native add-to-cart flow.
