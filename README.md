# Raga Guess 🎶

Live raga-guessing game for Carnatic concerts, pub-quiz style.

- **Moderator** creates a room (share the 5-letter code), then per song enters a title, optional timestamp, the secret raga and optional multiple-choice options. The answer stays on the moderator's device until **Reveal**.
- **Players** join with a code and any username, guess (free text with autocomplete, or tap an option), and can change their guess until the moderator locks it.
- Live **leaderboard**: 10 pts per correct raga, +5/+3/+1 for the first three correct. Spelling variants (Todi/Thodi, Shankarabharanam/Sankarabharanam) match.

Static page (`index.html`) on Firebase Realtime Database. Host with GitHub Pages (Settings → Pages → branch `master`, root). Review `database.rules.json` and apply it in the Firebase console.

`legacy_raga_app.html` is the original single-room prototype.

## Use it anywhere
It's a installable web app (PWA): open the link in any browser on a phone, tablet or PC; on a phone use *Add to Home Screen*. The host can tap **Share invite link** to send players straight into the room.
