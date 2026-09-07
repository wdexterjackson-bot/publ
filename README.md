# publ

Public legal pages for the **Ask Lellon** iOS app, served via GitHub Pages.

| File | Published at |
| --- | --- |
| `index.html` | `https://wdexterjackson-bot.github.io/publ/` |
| `privacy.html` | `https://wdexterjackson-bot.github.io/publ/privacy.html` |

## Enabling GitHub Pages

Settings → Pages → Source: **Deploy from a branch** → Branch `main`, folder `/ (root)`.
The pages go live a minute or so after the first push.

## Keeping the app in sync

The privacy policy URL is declared in two places and both must match whichever URL is live:

- `Lellon/Models/LegalLinks.swift` → `LegalLinks.privacyPolicy`
- The App Store Connect listing's Privacy Policy URL field

## Editing

Plain static HTML with no build step and no dependencies — edit, commit, push.
Update the effective date and the "Last updated" line in the footer whenever the
substance of the policy changes.
