# urbanapp landing page

Minimal, single-file landing page for **Urbanapp Kft.** — coder/terminal aesthetic,
no build step, no dependencies. Content mirrors [urbanapp.hu](https://www.urbanapp.hu).

```
.
├── index.html   # the whole site (HTML + inline CSS + SEO meta)
├── robots.txt
├── sitemap.xml
└── README.md
```

## Local preview

```
$ python3 -m http.server 8000   # then open http://localhost:8000
```

## Deploy (GitHub Pages)

1. Push this repo to GitHub.
2. **Settings → Pages → Source:** `Deploy from a branch` → `main` / `root`.
3. (Optional) add a `CNAME` file with `urbanapp.hu` for a custom domain.

Everything lives in `index.html`; edit text/colors there.
