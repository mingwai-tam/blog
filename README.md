# My Jekyll Blog

A blog built with Jekyll and hosted on GitHub Pages.

## Setup

1. **Install dependencies:**
   ```bash
   bundle install
   ```

2. **Run locally:**
   ```bash
   bundle exec jekyll serve
   ```
   Then visit `http://localhost:4000` in your browser.

3. **Build the site:**
   ```bash
   bundle exec jekyll build
   ```

## Configuration

Edit `_config.yml` to customize:
- Site title and description
- Your email and social media profiles
- Base URL and site URL for deployment

## Creating Posts

Add new posts in the `_posts` directory with the filename format: `YYYY-MM-DD-title.md`

Example front matter:
```yaml
---
layout: post
title: Your Post Title
date: 2026-05-06 12:00:00
categories: category-name
tags: tag1 tag2
---
```

## Directory Structure

```
├── _config.yml          # Site configuration
├── _posts/              # Blog posts (markdown files)
├── _layouts/            # HTML templates
├── _includes/           # Reusable HTML snippets
├── assets/              # CSS, images, etc.
├── index.md             # Homepage
├── about.md             # About page
├── Gemfile              # Ruby dependencies
└── README.md            # This file
```

## Deployment to GitHub Pages

1. Push this repo to GitHub
2. Go to repository Settings → Pages
3. Set source to main branch and save
4. Your blog will be available at `https://yourusername.github.io/blog/`

## Resources

- [Jekyll Documentation](https://jekyllrb.com/)
- [GitHub Pages Guide](https://pages.github.com/)
- [Minima Theme](https://github.com/jekyll/minima)
