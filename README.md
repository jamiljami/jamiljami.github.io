# Jamil Jami – Personal Website

This repo contains the source code for my personal website and portfolio:

👉 **Live site:** https://jamiljami.github.io  

It’s where I showcase my projects, experience, skills, and a bit of my brain 🧠

---

## What’s on the site?

The homepage is split into several sections:

- **About** – Who I am and what I’m about.
- **Projects** – Selected work and experiments.
- **Career** – Education, roles, and experience.
- **Awards** – Things I’ve been recognised for.
- **Skills** – A quick visual overview of my skill set.
- **Contact** – How to reach me.

Most of the content is driven by data files so I can update things without touching HTML directly.

---

## Tech stack

- **Static site generator:** Jekyll
- **Hosting:** GitHub Pages
- **Languages:** HTML, CSS, JavaScript, YAML
- **Data-driven sections:** `_data/*.yml`

---

## Content & configuration

A lot of the page content is configured through files in the `_data` directory instead of hard-coding everything in templates.

Some key files:

- `/_data/landing.yml` – Global settings for the landing page.
- `/_data/index/projects.yml` – Projects shown on the homepage.
- `/_data/index/careers.yml` – Timeline of my career/experience.
- `/_data/index/skills.yml` – Skills and their levels.
- `/_data/index/links.yml` – External links / social profiles.
- `/_data/blog.yml` – Blog navigation (if/when I add posts).

If I want to update text, add a new project, or tweak skills, I usually:

1. Edit the relevant `.yml` file in `_data/`.
2. Save the file.
3. Commit and push the changes to GitHub.
4. Let GitHub Pages rebuild and deploy the site.

---

## Developing locally

If I want to test the site locally before pushing changes, I use Jekyll.

### 1. Install Ruby

Install Ruby using one of:

- **macOS:** Homebrew or RVM  
- **Windows:** RubyInstaller  
- **Linux:** Use your distro’s package manager

(See the Ruby docs for detailed instructions.)

### 2. Install GitHub Pages / Jekyll

```bash
gem install github-pages
