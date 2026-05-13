# GoblinPass

Tiny vault. Minimal secrets.

GoblinPass is a local-first stateless password generator with a lightweight secure vault for password hints and email/login hints.

Inspired by LessPass, GoblinPass was created around a simple problem:

Most people remember their master password, but often forget the exact login, counter, alias, or settings needed to regenerate the same password later.

GoblinPass stores only minimal metadata to make deterministic password generation practical for everyday use.

---

# Features

* Stateless deterministic password generation
* Local-first design
* No cloud account required
* No master password storage
* Full generated passwords are never saved
* PIN-protected vault
* Password hints only
* Masked email/login storage
* Optional full login storage for random aliases
* Mobile PWA version
* Browser extension version

---

# What GoblinPass Stores

GoblinPass may store:

* Site/domain
* Masked login/email hints
* Optional full login (if enabled)
* Password hint (first few characters only)
* Counter value
* Password length
* Character settings

---

# What GoblinPass Does NOT Store

GoblinPass does NOT store:

* Your master password
* Full generated passwords
* Clipboard history
* Cloud backups
* Remote analytics
* Server-side vault data

---

# Security Notes

GoblinPass is designed to minimise stored secrets while keeping password regeneration practical.

Vault access is protected by a local PIN, but this project should currently be considered a lightweight privacy-focused password helper rather than a fully audited security product.

Always use strong master passwords and keep your device secure.

---

# How It Works

Passwords are generated deterministically using:

* Site/domain
* Login/email
* Master password
* Counter
* Password settings

The same inputs will always generate the same password.

---

# Browser Extension

Load unpacked extension:

1. Download GoblinPass
2. Open:

   * Chrome: `chrome://extensions`
   * Edge: `edge://extensions`
3. Enable Developer Mode
4. Click "Load unpacked"
5. Select the GoblinPass folder

---

# Mobile Version

GoblinPass Mobile is a local-first Progressive Web App (PWA).

You can:

* Open it in a mobile browser
* Add it to your Home Screen
* Use it offline after loading

---

# Open Source

GoblinPass is open source so users can inspect how password generation and local storage work.

---

# Disclaimer

Use GoblinPass at your own risk.

Always keep backups of important account recovery information. Losing your master password may permanently prevent password regeneration.

---

# Inspiration

Inspired by:

* LessPass
* Stateless password generation concepts
* Local-first privacy-focused tools
