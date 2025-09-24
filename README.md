# Google Ads Personal Automation (Node.js)

**Status:** WIP / personal tool — not a SaaS, not for resale.

This repository documents a private script I use to automate **my own** Google Ads account.
It reads basic reports and can create/update/pause campaigns, ad groups, ads, keywords, and budgets.

**Compliance**
- Uses the official Google Ads API and respects policies and rate limits.
- Single-user, single-account usage (no multi-client access).
- No data sharing or resale; data is stored locally.

**Auth**
- OAuth2 (scope: `https://www.googleapis.com/auth/adwords`) or a Service Account added as a user to my Google Ads account.

**Tech**
- Node.js (scripts only; not a hosted application).

