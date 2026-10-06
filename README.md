# paulkaneelil.github.io

Personal academic website built with Jekyll and the [Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/) theme (loaded as a remote theme).

## Where to edit things

| What | File |
|---|---|
| Name, sidebar bio, photo, links | `_config.yml` (`author:` section) |
| Top menu | `_data/navigation.yml` |
| Home page text | `index.md` |
| Research cards + project pages | `_projects/*.md` (one file per project; `weight` sets order) |
| Publications | `publications.md` |
| Teaching | `teaching.md` |
| CV | put PDF at `assets/pdfs/Kaneelil_CV.pdf` |
| Images | `assets/img/` |
| Styling tweaks | `assets/css/main.scss` |

## Preview locally (optional)

```
bundle install
bundle exec jekyll serve
```
Then open http://localhost:4000.
