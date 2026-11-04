# zhiding-sanguo-site

The public pages for **Three Kingdoms Dice (掷鼎三国)**: the privacy policy and support page that the App Store,
Google Play and the in-game About sheet link to. Plain static HTML, no build step, served by GitHub Pages.

| Page | URL |
|---|---|
| Landing | https://forevercrab321-svg.github.io/zhiding-sanguo-site/ |
| Privacy policy | https://forevercrab321-svg.github.io/zhiding-sanguo-site/privacy.html |
| Support | https://forevercrab321-svg.github.io/zhiding-sanguo-site/support.html |

## Publish (owner, once)

1. On GitHub create a **public** repository `forevercrab321-svg/zhiding-sanguo-site` (no template, no README).
2. Upload `index.html`, `privacy.html`, `support.html` and this `README.md` to the root of the `main` branch
   (Add file → Upload files → Commit).
3. Settings → Pages → Build and deployment → Source: *Deploy from a branch*, Branch: `main`, folder `/ (root)` → Save.
4. Wait 1–2 minutes, then open the three URLs above **on a phone on mobile data** and check each one loads.
5. Send a test email to forevercrab321@gmail.com and check it arrives (the pages and the game point people there).

## Keep in step

- The source of these files is the game repository, `docs/release/site/`. Edit there, then copy here.
- The support email and the two URLs are also in the game: `game/play/platform/support_contact.gd`. If you change the
  email or the address of these pages, change that file too and rebuild the game.
- If what the game does with data changes, update `privacy.html` (and its effective date) **and** the App Store App
  Privacy answers and the Google Play Data safety form before releasing that version.
- Never copy internal design or research documents from the game repository into this public repository.
