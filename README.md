# Yuta Yamate Portfolio

Personal portfolio and profile hub for [Yuta Yamate](https://www.yutayamate.com/), a product security engineer and manager based in Tokyo.

## Design

The site uses a custom "Signal Grid" visual system:

- A clear product security introduction and capability overview
- Restrained terminal-inspired details for technical identity
- Professional profiles and credentials with explicit visual priority
- Responsive light and dark themes
- Accessible semantic navigation and reduced-motion support

Portfolio content and profile links are managed in `_config.yml`. Jekyll renders the site with the layouts and components under `_layouts` and `_includes`.

## Local development

Requirements:

- Ruby 3.0 or later
- Bundler

Install dependencies and start Jekyll:

```bash
bundle install
bundle exec jekyll serve
```

The local site is available at `http://127.0.0.1:4000`.

Build without starting a server:

```bash
bundle exec jekyll build
```

## Deployment

Pushes to the `gh-pages` branch trigger `.github/workflows/jekyll-build-pages.yml`. The workflow builds the Jekyll site and deploys it to GitHub Pages.

## Attribution and license

This repository was originally forked from [harsh98trivedi/links](https://github.com/harsh98trivedi/links) and now uses a custom layout and design system.

Licensed under the [GNU General Public License v2.0](LICENSE).
