# sc-tcg

Documentation for the **sc-tcg** project — a static site built with [Jekyll](https://jekyllrb.com/) and hosted on [GitHub Pages](https://pages.github.com/).

**Deployed site:** [https://l-r0y.github.io/sc-tcg/](https://l-r0y.github.io/sc-tcg/)

## Table of contents

- [Getting started](#getting-started)
- [License](#license)

## Getting started

### Prerequisites

- [Ruby](https://www.ruby-lang.org/) (2.7+)
- [Bundler](https://bundler.io/)

### Build locally

```bash
# Install dependencies
bundle install

# Serve the site locally
bundle exec jekyll serve
```

The site will be available at `http://localhost:4000/sc-tcg/`.

## Deployment

This repository uses a GitHub Actions workflow (`.github/workflows/jekyll-deploy.yml`) that automatically builds and deploys the site to GitHub Pages on every push to the `main` branch.

## Project structure

```
sc-tcg/
├── .github/
│   └── workflows/
│       └── jekyll-deploy.yml   # CI/CD: build & deploy to GitHub Pages
├── _config.yml                 # Jekyll configuration
├── _data/
│   └── navigation.yml          # Header navigation menu
├── _includes/                  # Reusable HTML partials (theme)
├── _layouts/                   # Page layouts (theme)
├── _posts/                     # Blog posts
├── _sass/                      # Sass partials
├── assets/
│   ├── css/
│   │   └── main.scss           # Custom styles
│   └── img/                    # Images
├── Gemfile                     # Ruby gem dependencies
├── LICENSE
└── README.md
```

## License

This project is licensed under the [MIT License](LICENSE).
