# FeelTrail Public Site

This directory contains static HTML pages for FeelTrail's public-facing content.

## Purpose

These pages serve as:
- Privacy policy (public URL)
- Support and FAQ (public URL)
- Landing page with product information

## Files

- `index.html` — Landing page with product overview and links
- `privacy.html` — Privacy policy (English and Simplified Chinese)
- `support.html` — Support page with FAQ (English and Simplified Chinese)

## Design Principles

All pages follow these constraints:
- **Static HTML only** — No backend, no forms, no JavaScript required
- **No tracking** — Zero external scripts, analytics, or cookies
- **No external dependencies** — All styling is inline
- **Bilingual-ready** — Content in English and Simplified Chinese
- **Minimalist design** — Plain, calm, accessible layout
- **No medical claims** — Only factual statements about app features

## Local Testing

To test pages locally without deployment:

1. Open any `.html` file directly in a web browser
   ```
   # On Windows, you can drag the file into your browser or:
   start privacy.html
   ```

2. Verify all sections are readable
3. Verify links work (same-page navigation only)
4. Verify no external scripts load

## Deployment

**Important:** These files are prepared but NOT YET DEPLOYED.

To deploy publicly:
1. Founder chooses hosting method (GitHub Pages, custom server, Vercel, Netlify, etc.)
2. Upload these files to public URL
3. Confirm URLs are stable and will remain available
4. Update app to reference live URLs in Settings screen
5. Submit privacy policy and support URLs to App Store Connect

**Example URL structure:**
```
Privacy: https://[your-domain]/feeltrail/privacy
Support: https://[your-domain]/feeltrail/support
```

## Content Source

All content is based on:
- `Documents/84_public_privacy_support_page_content_final.md` — Finalized copy

## Bilingual Content

Each page includes:
- **English section** — Full English content
- **Simplified Chinese section** — Full Chinese translation (简体中文)
- **Clear language markers** — HTML comments separate sections

## No External Dependencies

✓ No external stylesheets
✓ No external JavaScript
✓ No fonts loaded from CDN
✓ No tracking pixels
✓ No analytics tags
✓ No forms that collect data
✓ No cookies

## Accessibility

All pages are designed to be:
- Accessible without JavaScript
- Readable in any browser
- Mobile-friendly
- No special plugins required

## Questions?

For production deployment questions, contact the FeelTrail founder.

---

**Status:** Prepared but not deployed (2026-05-17)
**Next:** Founder deploys to public URLs before App Store submission
