git init
git add.
git commit -m "Fisch Game - Initial Build."
git remote add origin https://github.com/YourName/fisch-game.git
git branch -M main
git push -u origin main
5. Deploy
Run this single command when ready:
bash
Copy
npm run deploy
This builds your game into the out/ folder and pushes it to a special gh-pages branch.
6. Enable GitHub Pages
Go to your repo's Settings → Pages
Under "Build and deployment", select:
Source: Deploy from a branch
Branch: gh-pages / root
Click Save
7. Wait & Play
Wait 1-2 minutes for deployment
Your game will be live at: https://YourName.github.io/fisch-game
Press Z in-game to access your Command Studio
You're all set! When you want to publish, just run npm run deploy and follow steps 6-7.

