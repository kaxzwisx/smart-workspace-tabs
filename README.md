# Smart-Workspace-Tabs Official Website

Official GitHub Pages website for the **Smart-Workspace-Tabs** Chrome Extension.

## 🌐 Live Pages & Structure

Built with pure, modern, dependency-free static HTML5 and CSS3:

```
.
├── .nojekyll                 # Ensures GitHub Pages serves all assets directly
├── index.html                # English Landing Page (Hero, Features, Preview, Install)
├── privacy.html              # English Privacy Policy (100% Local, Permissions Breakdown)
├── help.html                 # English Help & FAQ (Shortcuts, Tab Groups, Memory, Backups)
├── changelog.html            # English Version History & Roadmap
├── es/                       # Spanish Localization
│   ├── index.html            # Spanish Landing Page
│   ├── privacy.html          # Spanish Privacy Policy
│   ├── help.html             # Spanish Help & FAQ
│   └── changelog.html        # Spanish Changelog
└── assets/
    ├── css/
    │   └── style.css         # Responsive theme with Grupo Ōkami teal palette & Dark Mode
    ├── js/
    │   └── main.js           # Theme toggle, mobile menu, showcase tabs & FAQ accordions
    └── img/                  # High-resolution screenshots and extension icons
```

## 🎨 Branding & Palette

Follows the Grupo Ōkami design system:
- **Teal Primary:** `#009393`
- **Deep Teal (Accessible Buttons / Links):** `#007f82`
- **Bright Cyan:** `#00acb0`
- **Neutrals / Ink:** `#363f3e`, `#2a3231`, `#1b2121`
- **Light Tints:** `#eef6f9`, `#dceef0`

## 🚀 Local Preview

You can open `index.html` directly in your browser, or spin up a quick local web server:

```bash
# Using Python 3:
python3 -m http.server 8080

# Or using Node.js:
npx serve .
```

Then visit `http://localhost:8080`.

## 📦 Publishing to GitHub Pages

This repository is configured for GitHub Pages from the `main` branch root directory:

1. Stage and commit your files:
   ```bash
   git add .
   git commit -m "feat: initial release of official website (EN + ES)"
   ```

2. Push to GitHub:
   ```bash
   git push -u origin main
   ```

3. In GitHub Repository Settings:
   - Go to **Settings** &rsaquo; **Pages**.
   - Under **Build and deployment**:
     - **Source**: `Deploy from a branch`
     - **Branch**: `main`
     - **Folder**: `/ (root)`
   - Click **Save**.

Your website will be published live at:
`https://kaxzwisx.github.io/smart-workspace-tabs/` (or your configured custom domain).

