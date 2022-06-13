## Netlify-MkDocs

**MkDocs with Netlify (minimal configuration)**

- [Netlify](https://www.netlify.com/)
- [MkDocs](https://www.mkdocs.org/)

## How to use

1. Edit `mkdocs.yml` and `docs/index.md`, add more files if needed.
2. Add the pip package to `requirements.txt` . (Themes and plugins)
3. In Netlify, select `Import an existing project` and select the Git project.

## Build error

Many of the build error are that you mistyped `mkdocs.yml`
or you forgot to add the package to` requirements.txt`.
Check the file change immediately before the error occurred.

This is often not a problem with this project.
You should not open an issue for that.
