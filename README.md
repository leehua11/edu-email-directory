# EduMail Hub — Disposable Educational Email Directory & QA Testing Guide

A high-performance, modern, and SEO-optimized microsite dedicated to reviewing and showcasing disposable educational email services for developers, QA engineers, and testing automation.

> **Featured Top Pick**: [UES.edu.pl](https://www.ues.edu.pl/) — Instant, zero-registration temporary educational email service powered by Cloudflare Email Routing with a strict 24-hour auto-purge privacy policy.

---

## 🚀 Quick Deployment Guide to Netlify

This repository is built with pure static HTML and Tailwind CSS (CDN-powered). It requires **no build step**, **no Node.js dependencies**, and is 100% ready for instant deployment to [Netlify](https://app.netlify.com/).

### Step 1: Upload to Your GitHub Account

1. Go to [GitHub](https://github.com/new) and create a new repository (e.g. `edumail-hub` or `disposable-edu-mail-hub`). Leave it **Public**.
2. Open PowerShell or Terminal inside this directory (`ues-netlify-backlink-site`):
   ```bash
   git init
   git add .
   git commit -m "feat: initial commit for EduMail Hub SEO microsite"
   git branch -M main
   git remote add origin https://github.com/YOUR_GITHUB_USERNAME/YOUR_REPO_NAME.git
   git push -u origin main
   ```

### Step 2: Deploy on Netlify

1. Log into your [Netlify Dashboard](https://app.netlify.com/).
2. Click **"Add new site"** &rarr; **"Import an existing project"**.
3. Choose **GitHub** as your Git provider and authorize access.
4. Select the repository you just pushed.
5. In the deploy settings:
   - **Branch to deploy**: `main`
   - **Build command**: *(Leave blank)*
   - **Publish directory**: `.` *(or leave blank)*
6. Click **"Deploy site"**.
7. Netlify will generate an address like `https://your-site-name.netlify.app`. 
   *(Optional: You can change the subdomain in Site Configuration &rarr; Change site name, e.g. `edumail-directory.netlify.app`)*.

---


## 📄 License

MIT License. Free for personal and commercial distribution.
