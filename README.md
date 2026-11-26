# goober-ui

Signed over-the-air screen updates for a personal Android chat app.

- `ui.zip` holds only the app's screen code (HTML/JS). No character art, keys or personal data.
- `manifest.json` holds the version and an ECDSA P-256 signature. The app installs an update only if
  the signature matches the public key built into it; anything else is ignored.
