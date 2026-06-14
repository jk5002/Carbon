# CarbonLedger — Automated Scope 2 Carbon Accounting

**Half-hourly, DNO-region-matched carbon accounting from smart meter data. Audit-ready SECR reports. Built on Procode IDA & Loop.**

## What It Does

CarbonLedger ingests half-hourly smart meter data across your property portfolio, matches it to regional carbon intensity from the National Grid ESO API, and produces audit-ready SECR reports — automatically.

## Quick Deploy

This is a static site. Deploy to **GitHub Pages** in 3 steps:

1. Push this repo to GitHub
2. Go to **Settings → Pages**
3. Set source to `main` branch, root folder → Save

Your site will be live at `https://yourusername.github.io/carbon-ledger/`

## Waitlist Form

The waitlist form uses **Formspree** (free tier: 50 submissions/month). To enable:

1. Sign up at [formspree.io](https://formspree.io)
2. Create a new form — get your form ID
3. Open the browser console on the live site and run:
   ```js
   localStorage.setItem('carbonledger_form_id', 'your_form_id_here')
   ```
4. Refresh — submissions will now go to your email

Without Formspree, emails are stored in `localStorage` (demo mode).

## File Structure

```
carbon-ledger/
├── index.html      # Full site — everything self-contained
└── README.md
```

## Key Sections

- Hero with market stats
- How It Works (4 steps)
- Feature grid (9 cards)
- Competitive comparison table
- Interactive carbon savings calculator
- Compliance standards (SECR, UK SRS, GHG Protocol, ISAE 3000, ESOS)
- Market opportunity & revenue projections
- Sample SECR report preview
- Pricing (3 tiers)
- Target market segments
- FAQ
- Development roadmap (3 phases with budgets)
- Waitlist CTA
