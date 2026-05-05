# 💰 Ledger — Personal Budget Tracker

A fully featured personal finance app with Google Drive sync, installable on iPhone and desktop.

## Features
- Dashboard with daily balance & payday countdown
- Bill tracker with calendar view
- Transaction import from USAA CSV
- Income & paycheck tracker (gross → net)
- Credit card payoff planner with strategy comparison
- Google Drive sync across all devices
- Installable as a PWA on iPhone and desktop


## Updating the App
1. Get the new `BudgetTracker.html` from Claude
2. Rename it to `index.html`
3. Come back to this GitHub repository
4. Click on `index.html` → click the pencil (edit) icon → or drag-drop the new file
5. Click **Commit changes**
6. GitHub redeploys automatically in ~60 seconds

## Google Drive Setup
1. Go to [console.cloud.google.com](https://console.cloud.google.com)
2. Create a project → Enable Google Drive API
3. Google Auth Platform → Get Started → fill in branding
4. APIs & Services → Credentials → Create OAuth 2.0 Client ID
5. Application type: **Web application**
6. Authorized JavaScript origins: add your GitHub Pages URL (shown below your repo name)
7. Copy the Client ID → paste into the app Settings → Connect Drive
