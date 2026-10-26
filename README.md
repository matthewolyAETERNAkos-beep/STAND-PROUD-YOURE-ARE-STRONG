# Steel Ball Run (Windows app)

Electron wrapper around index.html.

## Build the .exe (easiest: GitHub)
1. Upload everything in this folder (including the .github folder) to your repo.
2. Go to Actions > "Build Windows app" > Run workflow.
3. When it finishes, download the "SteelBallRun-Windows" artifact: an installer and a portable .exe.

## Build locally (needs Node.js 20+)
    npm install
    npm run build
Output is in dist/. Use `npm start` to just run it.

Optional: put cover.jpg next to index.html for the background image.
