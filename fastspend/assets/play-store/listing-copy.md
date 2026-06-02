# Play Store Listing Copy — FastSpend

## App title (max 30 chars)

**FastSpend: 3-sec Money Tracker** (28 chars)

Alternates:
- `FastSpend — Quick Expense Log` (29 chars)
- `FastSpend: Spend in 3 Seconds` (29 chars)

## Short description (max 80 chars)

**Log money in 3 seconds. No accounts, no setup, just speed.** (60 chars)

Alternates:
- `The fastest spend tracker on Android. Widget · Voice · One-screen entry.` (72 chars)
- `Track your money in 3 seconds flat. Widget, voice, or a single screen.` (70 chars)

## Long description (max 4000 chars)

```
FastSpend is the money tracker that respects your time.

Every other expense app forces you through 6+ taps to log a coffee — pick an
account, a category, a sub-category, a date, a note, a payment method. By the
time you're done, you've forgotten what you were tracking.

FastSpend does one thing: it logs a spend in three seconds.

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

THREE WAYS TO LOG, ALL UNDER 3 SECONDS

→ HOME-SCREEN WIDGET
   Tap the amount. Tap a recent category. Saved. The app never opens.

→ VOICE COMMAND
   "Hey Google, log 50k coffee in FastSpend." Done. Hands-free.

→ ONE-SCREEN NUMPAD
   The app opens to the numpad — not a dashboard, not a menu. Type and save.

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

WHAT'S IN THE APP

• Amount + category. That's the whole data model.
• Spend AND income tracking — see your net cashflow.
• Monthly summary with category breakdown and donut chart.
• Swipe between months to compare.
• Smart recent-categories: your most-used spends are always one tap away.
• One-tap undo on every save. Misclick? No problem.
• Default categories that actually make sense (Coffee, Food, Transport,
  Groceries, Shopping, Bills, Entertainment, Health, Salary, Bonus).
• Material You theming — adapts to your wallpaper colors.

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

PRIVATE BY DEFAULT

Your data lives on your phone. No account required. No tracking. No ads. Ever.

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

FASTSPEND PLUS — OPTIONAL

If you want your data synced between your phone, tablet, and any other Android
device, FastSpend Plus adds:

• Real-time cloud sync (encrypted)
• Automatic backups
• CSV export for spreadsheets
• Priority support

$1.99/month or $14.99/year. 7-day free trial. Cancel anytime.

The free tier is fully functional forever. Plus is for sync — not for unlocking
features that should have been free.

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

WHAT WE DON'T DO

• No bank linking. No SMS scraping. No receipt OCR. No social features.
• No "premium themes" or "premium reports" gated behind a paywall.
• No nag screens, no daily reminders, no streak gamification.
• No analytics tracking. Crashlytics only, fully disclosed.

We picked one thing — fast logging — and went deep on it.

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

BUILT FOR ANDROID

• Material 3 (Material You) design
• Home-screen widgets (4×1 and 4×2)
• Google Assistant App Actions for voice
• Themed icons (Android 13+)
• Quick Settings tile
• Offline-first — works without internet

Requires Android 8.0 or newer.

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

Questions, ideas, complaints? hello@fastspend.app
```

**Character count:** ~2,400 chars (well under the 4000 limit)

---

## Play Store metadata checklist

### Required

- [x] **App icon** — 512×512 PNG (export from `app-icon/ic_launcher_foreground.svg` + `_background.svg` at 512px)
- [x] **Feature graphic** — 1024×500 PNG (export from `feature-graphic.svg`)
- [x] **Phone screenshots** — minimum 2, maximum 8, 1080×1920 portrait PNG (export the 5 `screenshot-*.svg` files)
- [ ] **App title** — see above (max 30 chars)
- [ ] **Short description** — see above (max 80 chars)
- [ ] **Long description** — see above (max 4000 chars)
- [ ] **Privacy policy URL** — must be hosted publicly; required for any app that handles user data
- [ ] **Contact email** — `hello@fastspend.app` (or your choice)
- [ ] **Category** — "Finance" primary, "Productivity" secondary
- [ ] **Content rating** — IARC questionnaire (likely Everyone)

### Recommended

- [ ] **Promo video** — 30-second screen recording showing the 3-second flow
- [ ] **Tablet screenshots** — 7" and 10" tablet sizes if supporting tablets
- [ ] **TV/Wear screenshots** — N/A for v1

---

## Export-to-PNG instructions

Play Console requires PNG or JPEG, not SVG. To convert:

**Option A — Inkscape (free, command line):**
```bash
inkscape feature-graphic.svg --export-type=png --export-filename=feature-graphic.png --export-width=1024 --export-height=500
inkscape screenshot-1-numpad.svg --export-type=png --export-filename=screenshot-1-numpad.png --export-width=1080 --export-height=1920
# ...repeat for screenshot-2 through 5
```

**Option B — rsvg-convert (lightweight):**
```bash
brew install librsvg
rsvg-convert -w 1024 -h 500 feature-graphic.svg -o feature-graphic.png
rsvg-convert -w 1080 -h 1920 screenshot-1-numpad.svg -o screenshot-1-numpad.png
```

**Option C — Chrome headless:**
```bash
chrome --headless --screenshot=feature-graphic.png --window-size=1024,500 feature-graphic.svg
```

I can run any of these for you if you want PNGs ready-to-upload — just say the word.
