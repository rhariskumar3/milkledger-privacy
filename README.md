# Milk Ledger — policy pages

Privacy policy, terms of use and data-deletion instructions for the
**Milk Ledger** Android app, served by GitHub Pages.

| Page | URL |
|---|---|
| Privacy policy | https://rhariskumar3.github.io/milkledger-privacy/ |
| Terms of use | https://rhariskumar3.github.io/milkledger-privacy/terms.html |
| Delete your data | https://rhariskumar3.github.io/milkledger-privacy/delete-data.html |

The privacy policy URL is the one Google Play requires on the app's store listing;
the deletion page is the one Play asks for under **Data safety → data deletion**.

Plain HTML with a single shared stylesheet, no build step. Edit and push; Pages redeploys.

## Keep this in step with the app

The claims here are specific and checkable, which is the point — but it also means they
can go stale. Re-read this repo before any release that:

- adds a permission (the permission table lists all four by name),
- adds a network call of any kind (the whole policy rests on there being no
  `INTERNET` permission),
- adds analytics, crash reporting or advertising,
- changes what the cleanup feature deletes.
