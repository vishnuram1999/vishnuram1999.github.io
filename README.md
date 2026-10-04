# viking71 — personal portfolio

Jekyll portfolio for Vishnuram Rajkumar, hosted at https://vishnuram1999.github.io.

## Design

- Custom dark layouts in `_layouts/`, with teal accents and system fonts.
- Responsive, CSS-only interface in `assets/css/style.css`.
- Existing writeups live in `_posts/`; the homepage lists them automatically.
- Resume and social links are preserved from the deployed site.

## Local preview

Use Ruby with Bundler 2.3.21 (the version specified by `Gemfile.lock`):

```sh
bundle install
bundle exec jekyll serve
```

Open http://localhost:4000. For a production build:

```sh
JEKYLL_ENV=production bundle exec jekyll build
```

## Publishing

GitHub Pages currently deploys from `gh-pages`, not `main`. These source files
were copied from that branch into the local `main` working tree for redesign.
Editing or committing `main` alone does not update the live website.

After reviewing the design, publish the source changes to `gh-pages`, or explicitly
change the Pages publishing source in GitHub Settings → Pages. No deployment
configuration has been changed as part of this redesign.
