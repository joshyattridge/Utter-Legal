# Utter Legal

Terms of Service and Privacy Policy for the Utter daily voice journal app. Hosted via GitHub Pages.

## URLs

- **Index:** https://joshyattridge.github.io/Utter-Legal/
- **Terms of Service:** https://joshyattridge.github.io/Utter-Legal/terms.html
- **Privacy Policy:** https://joshyattridge.github.io/Utter-Legal/privacy.html

## Setup (first time)

1. **Create the repo on GitHub**
   - Go to [github.com/new](https://github.com/new)
   - Name: `Utter-Legal`
   - Set to **Public**
   - Do not initialize with README (this folder already has one)
   - Create repository

2. **Push this folder**
   ```bash
   cd Utter-Legal
   git init
   git add .
   git commit -m "Add Terms of Service and Privacy Policy"
   git branch -M main
   git remote add origin https://github.com/joshyattridge/Utter-Legal.git
   git push -u origin main
   ```

3. **Enable GitHub Pages**
   - Repo → **Settings** → **Pages**
   - Source: **Deploy from a branch**
   - Branch: **main**, folder: **/ (root)**
   - Save

4. Wait 1–2 minutes. Site will be live at the URLs above.
