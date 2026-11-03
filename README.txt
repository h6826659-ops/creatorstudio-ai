# CreatorStudio AI — Free Starter

A self-contained Hindi/English video-planning web app. It runs in a browser and can be installed on Android as a PWA.

## Features
- Script draft builder (template-based, no external AI API)
- Script-to-scenes storyboard and editable visual prompts
- Voiceover text cleanup/preparation
- Thumbnail concept and image prompt
- YouTube title, description, tags and hashtags draft
- Save/load/delete projects using browser localStorage
- Export text files
- PWA manifest and offline cache

## Run on a computer
1. Extract the ZIP.
2. Open `index.html` in Chrome or Edge.
3. For install/offline PWA features, serve the folder from HTTPS hosting or localhost (opening the HTML file directly does not enable service workers).

## Use on Android
1. Upload the extracted folder to an HTTPS static host (for example GitHub Pages).
2. Open the published site in Chrome on Android.
3. Browser menu → **Add to Home screen** or **Install app**.

## Free hosting option: GitHub Pages
Create a public GitHub repository, upload `index.html`, `manifest.json`, `sw.js`, and `icon.svg` to the repository root, then enable Pages in repository Settings → Pages → Deploy from branch → main/root. Wait for the public HTTPS URL.

## Important limitations
This is a functional starter workspace, not a connected generative-AI service. Script, SEO and thumbnail suggestions are template-generated. Real AI script generation, image/video generation and speech synthesis require a model/service integration; free tiers and quotas can change. Do not paste private information into public AI services.

Projects are saved only in the browser/device where they were created. Use the Download buttons to back up your work.
