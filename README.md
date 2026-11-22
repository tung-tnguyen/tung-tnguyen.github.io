# Tung (Tristan) Nguyen — Portfolio

This is the source code for my personal portfolio site. It contains a short introduction, my skills, and case studies for projects I have worked on in school, research, internships, and on my own.

The site is built with Hugo and is deployed through GitHub Pages.

## Run it locally

Install Hugo Extended, then run:

```bash
hugo server
```

Open [http://localhost:1313](http://localhost:1313) in your browser.

To create a production build:

```bash
hugo --minify
```

Hugo writes the finished site to `public/`.

## Update the site

Project cards and project-page content are stored in `data/projects.yaml`. Each project also has a page under `content/projects/` so it has its own URL.

When adding a project:

1. Add its metadata and case-study sections to `data/projects.yaml`.
2. Add a matching Markdown file under `content/projects/`.
3. Add any approved images or figures when they are ready.

## Personal files

- Profile photo: `assets/images/profile.jpg`
- Resume: `static/resume.pdf`
- Contact links: `layouts/index.html`

## Deployment

Pushing to `main` runs the GitHub Actions workflow in `.github/workflows/hugo.yml`. The published site is:

<https://tung-tnguyen.github.io/>
