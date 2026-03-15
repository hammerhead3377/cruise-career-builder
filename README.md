# 🚢 Cruise Career Builder

> A free, offline-ready resume builder for Filipino cruise ship applicants.

No account. No server. No data leaves your device. Fill in the form, get a professional resume — screenshot and send.

---

## Live App

**👉 [Open Cruise Career Builder](https://hammerhead3377.github.io/cruise-career-builder/)**

Works in any browser. Install on Android for the full app experience (see below).

---

## What It Does

- 6-step guided form — Personal Info, Documents, Education, Work Experience, Cruise Target, Skills
- Generates a formatted, print-ready resume instantly
- Covers STCW, SIRB, PEME, certifications — everything cruise recruiters look for
- Works **offline** after first visit
- Installable on Android — no app store required

---

## Install on Android (Free)

1. Open **Chrome** on your Android phone
2. Visit the live app link above
3. Tap the **three-dot menu** → **"Add to Home Screen"**
4. Tap **Add**

The app icon appears on your home screen. Opens fullscreen, works without internet.

---

## Use It on Desktop

Just open `index.html` in any browser — Chrome, Firefox, Edge.
No setup, no install, no internet needed after the first load.

---

## Self-Host or Customize

```bash
# Clone the repo
git clone https://github.com/hammerhead3377/cruise-career-builder.git
cd cruise-career-builder

# Open directly in browser
xdg-open index.html        # Linux
open index.html            # Mac
start index.html           # Windows
```

All logic is in `index.html` — single file, no dependencies, no build step.

---

## Deploy Your Own Version (GitHub Pages)

```bash
# Fork this repo on GitHub, then:
git clone https://github.com/YOUR_USERNAME/cruise-career-builder.git
cd cruise-career-builder

# Make your changes to index.html
# Then push:
git add .
git commit -m "My customizations"
git push

# Enable GitHub Pages:
# GitHub repo → Settings → Pages → Source: main branch / root
```

Your version will be live at:
`https://YOUR_USERNAME.github.io/cruise-career-builder/`

---

## File Structure

```
cruise-career-builder/
├── index.html       # The entire app — form + resume generator
├── manifest.json    # PWA config — makes it installable on Android
├── sw.js            # Service worker — enables offline use
├── icon-192.png     # Home screen icon
└── icon-512.png     # Splash screen icon
```

---

## Who This Is For

Built with Filipino maritime workers in mind — particularly those in Cebu and the Visayas preparing applications for:

- Royal Caribbean, Carnival, MSC, Norwegian, Costa, Princess
- Hospitality roles: Cabin Steward, Wait Staff, Bartender, Spa, Receptionist
- First-time applicants who need help structuring their experience

---

## Acknowledgements

Concept by **Thomas**.
Built with [Claude](https://claude.ai) (Anthropic).

---

## License

MIT — free to use, fork, and customize for your community.
