# Khalid Shams IT138 Blog

GitHub Pages technical learning portfolio for Khalid Shams and the IT138 Linux+ class.

Live site:

```text
https://khalidshams-tech.github.io/blogIT138/
```

## Main Files

```text
blogIT138/
+-- _config.yml
+-- index.md
+-- linux.md
+-- week1.md
+-- week3.md
+-- legacy-portfolio.html
+-- resume.html
+-- assets/
    +-- css/
        +-- jekyll.css
        +-- styles.css
```

## Site Structure

- `index.md` - Home page
- `linux.md` - Linux (IT138) blog tab
- `week1.md` - Week 1 blog post
- `week3.md` - Week 3 blog post
- `assets/css/jekyll.css` - simple styling for the Markdown/Jekyll pages
- `legacy-portfolio.html` - preserved version of the previous HTML portfolio

## How to Add a New Weekly Blog Post

1. Create a new Markdown file, for example:

```text
week4.md
```

2. Add front matter at the top:

```markdown
---
title: Week 4 | Your Post Title
---
```

3. Add the same navigation and footer used in the other weekly files.

4. Add the post link only on `linux.md`.

Important: weekly posts should stay under the **Linux (IT138)** tab, not on the home page.

## GitHub Pages

This project uses simple Markdown and Jekyll-compatible GitHub Pages files. No complex framework is required.
