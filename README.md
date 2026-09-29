# Prada & Rina — Romantic Bromo Wedding Invitation

Responsive starter website featuring a rose-white envelope opening, romantic floating rose petals (no leafy decorations), Bromo photo backgrounds, bride/groom photo slots, event details, countdown, gallery, RSVP via WhatsApp, gift account copy, and guest-name personalization by URL.

## Files
- `index.html` — page content
- `style.css` — responsive design and animations
- `script.js` — envelope animation, guest URL, countdown, RSVP, music, copy-account button
- `assets/` — add your images and optional music here

## Add your real photos
Add these files to `assets/`:
- `bromo.jpg` — your chosen real Gunung Bromo photo (used as the main background)
- `bride-hijab.jpg` — bride portrait wearing hijab
- `groom.jpg` — groom portrait
- `music.mp3` — optional background music

The design gracefully shows colored placeholder backgrounds until photos are added. For best results, use a wide landscape photo for `bromo.jpg` and portrait photos for the couple.

## Personalize before publishing
In `script.js`:
- Replace `6281234567890` with the couple's WhatsApp number (international digits only).
- Replace `0000000000` with the wedding gift account number.

In `index.html`, update bank name/account holder details. The event venue, map, dates, and names are already filled in from the provided details.

## Guest link
Add `?to=Guest%20Name` to the published URL, for example:
`https://YOUR-USERNAME.github.io/YOUR-REPOSITORY/?to=Mr%20Andi%20and%20Family`

## Publish with GitHub Pages
1. Upload the project files to a GitHub repository.
2. Open **Settings → Pages**.
3. Under build and deployment, choose **Deploy from a branch**, branch `main`, folder `/(root)`, then Save.
4. Wait for the published URL to appear in Pages settings.
