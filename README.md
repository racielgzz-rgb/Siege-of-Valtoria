⚔️ Siege of Valtoria







A browser-based 3D medieval siege strategy game. Command the attackers and break through the walls of Valtoria, or take command of the defenders and hold the line — play against a friend or the built-in AI.
▶ Play Siege of Valtoria (live once you complete the one-time deploy steps below)



About the Game

Siege of Valtoria is a turn-based siege battle set on a rotatable 3D battlefield. Manage resources, watch wall integrity drop as the assault presses on, and react before the walls breach.




Game modes: Player vs. Player (local), Attack the AI defenders, or Defend against the AI
3D battlefield: drag to rotate, scroll to zoom
Live battle log tracking every exchange
Resource and wall-integrity management under time pressure
Built with React and Three.js, compiled into a single self-contained HTML file — no installation, server, or build step required. It just opens and plays in any modern browser.




Playing Locally
Download index.html and open it directly in any modern browser (Chrome, Firefox, Edge, Safari). No server or install needed.

Deploying This Page to GitHub Pages
You already have this game — this repo just needs to go live. Here's the fastest way, using GitHub's website (no command line required):

Go to github.com/new and create a new repository (e.g. siege-of-valtoria). Keep it public and don't initialize it with a README (you already have one here).
On the new repo's page, click "uploading an existing file" (or drag-and-drop).
Upload both index.html and README.md from this folder.
Commit the upload directly to the main branch.
Go to Settings → Pages (left sidebar).
Under Build and deployment, set Source to "Deploy from a branch," pick branch main and folder / (root), then click Save.
Wait about a minute, then refresh — GitHub will confirm your live URL at the top of the Pages settings screen: https://racielgzz-rgb.github.io/siege-of-valtoria/
That URL is now your live, shareable game page.

Prefer the command line?
bash git init git add index.html README.md git commit -m "Add Siege of Valtoria game page" git branch -M main git remote add origin https://github.com/racielgzz-rgb/siege-of-valtoria.git git push -u origin main

Then enable Pages the same way as step 5–6 above.




Files
index.html — the complete game, fully self-contained (React + Three.js bundled in)
README.md — this file
