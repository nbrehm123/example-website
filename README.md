# My Website

A simple personal website for learning Git and GitHub.

## Files

- `index.html` — the main page structure
- `style.css` — all styling and layout
- `images/` — place any images here and reference them in index.html

## Getting started with Git

```bash
# Initialise the repo (first time only)
git init

# Stage all files
git add .

# Make your first commit
git commit -m "Initial commit"

# Connect to GitHub and push
git remote add origin https://github.com/yourname/my-website.git
git push -u origin main
```

## Making changes

```bash
# Create a branch for a new feature
git checkout -b my-new-feature

# After editing files, stage and commit
git add .
git commit -m "Describe what you changed"

# Merge back to main
git checkout main
git merge my-new-feature
```
