# Deploy to GitHub Pages

## 1. Create the repo on GitHub

1. Go to **https://github.com/new**
2. **Repository name:** `Rajadarshini-Saravanan` (or any name you like)
3. **Public**, leave "Add a README" **unchecked** (you already have one)
4. Click **Create repository**

## 2. Push this folder

In a terminal, from this folder (`RajaDharshini/Website`), run (replace `YOUR_USERNAME` with your GitHub username):

```bash
cd /Users/gouthamsaie/Documents/R-Team/RajaDharshini/Website

git remote add origin https://github.com/YOUR_USERNAME/Rajadarshini-Saravanan.git
git branch -M main
git push -u origin main
```

## 3. Turn on GitHub Pages

1. On the repo page, go to **Settings → Pages**
2. Under **Source**, choose **Deploy from a branch**
3. Branch: **main**, folder: **/ (root)**
4. Save. In 1–2 minutes the site will be live at:

   **https://YOUR_USERNAME.github.io/Rajadarshini-Saravanan/**

## Optional: GitHub CLI

If you install [GitHub CLI](https://cli.github.com/) and run `gh auth login`, you can create and push in one go:

```bash
cd /Users/gouthamsaie/Documents/R-Team/RajaDharshini/Website
gh repo create Rajadarshini-Saravanan --public --source=. --remote=origin --push
```

Then enable Pages in **Settings → Pages** as above.
