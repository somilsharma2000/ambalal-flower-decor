# Ambalal Flower Decor — Official Website

**Client:** Ambalal Flower Decor · Jaipur, Rajasthan
**Contact:** Mohit Saini · +91 97829 95530
**Product:** Premium wedding-florist website + WhatsApp lead-capture system

---

## What's in this package

| Deliverable | Details |
|---|---|
| 🌹 **Premium one-page website** | Mobile-first, fast-loading, wedding-premium design |
| 💬 **WhatsApp lead capture** | Every CTA + smart enquiry form → direct WhatsApp enquiry with details |
| 🗄️ **Enquiry CRM** | Every form submission saved as a database record (name, phone, date, budget, status) |
| 🔍 **SEO-ready** | Meta tags, Open Graph, Google LocalBusiness schema, sitemap.xml, robots.txt |
| 📱 **QR code** | `qr-code.svg` — print on business cards, banners, vehicle branding → opens website |
| 🚀 **One-command deploy** | GitHub Pages / Netlify — zero hosting cost (~₹0/month) |

## Tech

- Pure HTML + CSS + vanilla JS — **no framework, no build step, nothing to break**
- Single `index.html` — loads in under 2s even on 3G
- Works on every phone browser (Jaipur traffic is 70%+ mobile)

## Deploy

**Option 1 — GitHub Pages (free):**
1. Push this repo to GitHub
2. Repo Settings → Pages → Branch: `main` → Save
3. Live at `https://<username>.github.io/ambalal-flower-decor/`

**Option 2 — Netlify (free, custom domain):**
1. Drag-and-drop this folder at app.netlify.com
2. Connect domain `ambalalflowerdecor.in` in domain settings

**Custom domain:** after purchase, create a `CNAME` file here containing the domain name, or set it in the hosting dashboard.

## Update workflow (for the developer)

- Photos/pricing text live directly in `index.html` — search for the section and edit
- Monthly content updates (new gallery photos, new reviews) = retainer work
- Client's WhatsApp number appears in the `wa.me` links — change in one find-replace

## Enquiry backend

Form submissions POST to a Base44 backend function which saves them to an `Enquiry` entity:
`New → Contacted → Quoted → Won/Lost` — a mini-CRM for every lead.

---
*Built with care for Ambalal Flower Decor. All rights reserved by the client.*
