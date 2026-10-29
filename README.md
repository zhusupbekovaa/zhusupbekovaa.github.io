# My Site

A small personal website and blog built with Jekyll and GitHub Pages.

## Put it online

1. Create a GitHub repo named `yourname.github.io` (public).
2. Edit `_config.yml`: set `title`, `email`, `github_username` and `url`.
3. Upload everything in this folder to the repo root (or `git push`).
4. In the repo go to **Settings > Pages**, choose **Deploy from a branch**, branch `main`, folder `/ (root)`.
5. Wait about a minute, then open `https://yourname.github.io`.

```bash
git init
git add .
git commit -m "Initial site"
git branch -M main
git remote add origin https://github.com/yourname/yourname.github.io.git
git push -u origin main
```

## Customize

| What | Where |
|---|---|
| Name, description, links | `_config.yml` |
| Colors and fonts | `assets/css/style.scss` (variables at the top) |
| About page | `about.md` |
| Your projects | `projects.md` (copy a `project-card` block per project) |
| Blog posts | `_posts/YYYY-MM-DD-title.md` |

## Preview locally (optional)

Needs Ruby. Then:

```bash
bundle install
bundle exec jekyll serve
```

Open http://localhost:4000.
