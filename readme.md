# Story Haven

A frontend-only website for three friends to share and view collaborative stories.

## Setup
1. Place all files in a single directory.
2. Ensure the `pictures/` folder contains `characters/`, `main-covers/`, and `sub-covers/` with images.
3. Open `index.html` in a browser. Use a local server (e.g., Live Server in VS Code) to avoid CORS issues with JSON fetching.
4. Edit `data/stories.json` and `data/characters.json` to add your content.

## Notes
- Images are placeholders; replace with your own in the `pictures/` subfolders.
- The site uses Bootstrap 5 for styling and is responsive on desktop and mobile.
- No backend is used; all data is stored in JSON files.
- If the site doesn’t load correctly, ensure the Bootstrap CDN is accessible.