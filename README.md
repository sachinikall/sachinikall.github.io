# Sachin Gangwar — Portfolio

This is Sachin Gangwar's static production engineering portfolio. It has a fresh Git history connected to `https://github.com/sachinikall/sachinikall.github.io.git`, with no history or workflows from the previous site. It needs no build dependencies.

## Publish to sachinikall.github.io

Your empty repository is `https://github.com/sachinikall/sachinikall.github.io`.

Git and GitHub CLI are installed on this computer. This folder has its first commit on `main`. Open a new PowerShell window and run:

```powershell
cd "C:\Users\sachin gangawar\OneDrive\Desktop\MyWebsite\sachinikall.github.io"
gh auth login
gh auth setup-git
git push -u origin main
```

Complete GitHub's browser sign-in when prompted. Then open **Settings → Pages** in the repository. Under **Build and deployment**, choose **Deploy from a branch**, then select `main` and `/(root)`. The published address will be `https://sachinikall.github.io/`.

The site uses relative asset paths. Edit `index.html` to update career and contact information; edit `site/style.css` to change the design.
