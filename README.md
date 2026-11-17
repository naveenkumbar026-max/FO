# F&O Trading Tracker

A mobile-friendly, browser-based F&O trading journal.

## Features
- Daily trade entry with instrument, segment, position, quantity, gross P&L, charges, capital used and notes
- Net P&L calculation (gross P&L minus charges)
- Dashboard totals and a daily P&L chart
- Trade history with month and instrument filters
- Monthly P&L report
- Starting capital and estimated current capital tracking
- JSON backup export and import
- Starts accepting trade dates from 3 November 2026

## Publish using GitHub Pages
1. Sign in to https://github.com/
2. Create a new repository, for example `fo-trading-tracker`.
3. Upload `index.html` (and this README if desired) to the repository root.
4. Open the repository's **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select branch `main` and folder `/ (root)`, then Save.
7. Wait for GitHub Pages to publish. Your URL will look like:
   `https://YOUR-USERNAME.github.io/fo-trading-tracker/`

## Data storage and backup
This basic version stores records in the browser's `localStorage` on the device/browser where you use it. It does not sync between devices and does not send records to a server. Use **Export backup (JSON)** regularly. Importing a backup replaces the currently stored trades and capital.

If you clear browser/site data, switch browsers, or use another device, the saved records will not automatically appear there.

## Important
This is a personal record-keeping tool, not a broker integration or investment advice. Enter actual brokerage and statutory charges yourself. Estimated current capital is starting capital plus recorded net P&L; it is not a live broker balance.
