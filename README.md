# Ronard G. Paña — academic website

Source for [ronardgpana.github.io](https://ronardgpana.github.io), built with [Hugo](https://gohugo.io) and the [PaperMod](https://github.com/adityatelange/hugo-PaperMod) theme.

## Where things live

| What | File |
| --- | --- |
| Name, bio, profile photo, social links, menu | `config.yml` |
| Publications | `content/publications/_index.md` |
| Projects (one file per project; `p0.md` is the group heading) | `content/projects/` |
| Work experience | `content/work-experience/_index.md` |
| Education | `content/education/_index.md` |
| Conferences | `content/conferences/_index.md` |
| News (shown on the home page under the bio; newest first) | `content/news/index.md` |
| Images and PDFs (served from the site root, e.g. `/profile_pana.jpg`) | `static/` |

To add a project thumbnail, put the image in `static/` and set `image: "/your-image.png"` in the project's front matter.

## Preview locally

Install [Hugo extended 0.111.3](https://github.com/gohugoio/hugo/releases/tag/v0.111.3) (the version the deploy workflow uses), then run:

```bash
hugo server
```

## Deploying

Pushing to `main` builds the site and publishes it to the `gh-pages` branch (Settings → Pages should serve from `gh-pages`). Pull requests only build the site, so a broken change shows up as a failed check before it goes live.

## Credits

- Theme: [PaperMod](https://github.com/adityatelange/hugo-PaperMod) (MIT), vendored in `themes/PaperMod`.
- Layout and style overrides in `layouts/` and `assets/css/` are adapted from [SamiaKabir/samiakabir.github.io](https://github.com/SamiaKabir/samiakabir.github.io) (MIT, © 2023 Samia Kabir; see `LICENSE-samiakabir`).
