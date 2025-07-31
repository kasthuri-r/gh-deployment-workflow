# GitHub Actions Deployment Workflow

This project demonstrates how to automate the deployment of a static website using **GitHub Actions** and **GitHub Pages**.  
It implements a Continuous Deployment (CD) workflow — whenever the `index.html` file is updated in the `main` branch, the site is automatically redeployed.

**Live Site**: [kasthuri-r.github.io/gh-deployment-workflow](https://kasthuri-r.github.io/gh-deployment-workflow/)

**Project Source:** [roadmap.sh/projects/github-actions-deployment-workflow](https://roadmap.sh/projects/github-actions-deployment-workflow)

---

## Project Structure

```markdown

gh-deployment-workflow/
│
├── index.html # Static website file (auto-deployed)
├── .github/
│ └── workflows/
│ └── deploy.yml # GitHub Actions deployment workflow
└── README.md # Project overview and usage

```

---

## Workflow Overview

- **Continuous Deployment** using GitHub Actions
- Auto-deploys only when `index.html` is changed
- Runs GitHub Actions workflow (`deploy.yml`)
- Pushes to `gh-pages` branch
- Clean and minimal HTML page saying “Hello, GitHub Actions!”
- Easy to extend for personal portfolios or static site generators

---

## Tech Used

- GitHub Actions
- GitHub Pages
- Static HTML

---

[![Deploy to GitHub Pages](https://img.shields.io/badge/GitHub-Pages-blue?logo=github)](https://kasthuri-r.github.io/gh-deployment-workflow/)
