# fadhlirahim.github.io

Personal site. Static HTML and CSS, no build step, no dependencies.

Served by GitHub Pages from `main` at the repository root.

```
index.html    all markup and copy
style.css     all styles
favicon.svg   clips on tracks, with a playhead
.nojekyll     serve files verbatim, skip Jekyll
```

## Local preview

```sh
python3 -m http.server 4000
```

Then open <http://localhost:4000>.

## Deploying

Push to `main`. Pages picks it up in under a minute.
