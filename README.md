# valeriolomonaco.com

Personal academic website of Valerio Lo Monaco (University of Bergamo), served by GitHub Pages at https://valeriolomonaco.com.

## Where things live

- `_config.yml`: site title, sidebar profile, links and social-sharing settings
- `_pages/`: the About, Publications and Privacy pages
- `_publications/`: one Markdown file per publication
- `_data/navigation.yml`: the links in the navigation bar
- `images/`: profile photo and favicons

## Running locally

```bash
bundle install
bundle exec jekyll serve -l -H localhost
```

Then open http://localhost:4000. Changes to `_config.yml` need a restart of the server.

## Credits

Built on the [Academic Pages](https://github.com/academicpages/academicpages.github.io) template, which derives from the [Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/) © 2016 Michael Rose. Both are released under the MIT License (see `LICENSE`).
