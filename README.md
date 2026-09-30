# kmoza.github.io

Personal developer blog, built with [Jekyll](https://jekyllrb.com/) and the [Chirpy](https://github.com/cotes2020/jekyll-theme-chirpy) theme, published on GitHub Pages.

## Write a post

Add a Markdown file under `_posts` named `YYYY-MM-DD-title.md`:

```markdown
---
title: Post title
date: 2026-09-30 19:00:00 +0530
categories: [Blog]
tags: [notes]
---

Post content.
```

## Run locally

```shell
bundle install
bundle exec jekyll serve
```

The site is then available at <http://127.0.0.1:4000>.

## Deploy

Pushes to `main` run `.github/workflows/pages-deploy.yml`. In the repository settings, **Pages → Build and deployment → Source** must be **GitHub Actions**.

The public site is <https://kmoza.github.io>.
