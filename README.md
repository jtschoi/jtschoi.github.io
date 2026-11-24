# jtschoi.github.io

Personal academic website of Junho Choi, built with Jekyll and the
[Minimal Mistakes](https://github.com/mmistakes/minimal-mistakes) remote theme
and served by GitHub Pages at <https://jtschoi.github.io/>.

## Where things live

- `index.md`: home page (bio)
- `_pages/`: Research, Teaching, CV, Misc and 404 pages
- `_data/navigation.yml`: top navigation menu
- `_config.yml`: site settings and sidebar (name, avatar, bio, links)
- `assets/pdf/`: CV, papers, slides and posters
- `assets/images/`: avatar and photos
- `assets/css/main.scss`: style overrides

## Preview locally

Use Ruby 3.1 or older (for example via rbenv). The `github-pages` gem pins
Jekyll 3.9, whose Liquid version fails on Ruby 3.2+ with
"undefined method `tainted?'". GitHub Pages itself is unaffected.

```bash
bundle install
bundle exec jekyll serve
```

Then open <http://localhost:4000>. Restart the server after editing `_config.yml`.
