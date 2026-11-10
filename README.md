# occamolab.org

**Live site:** [https://occamolab.org](https://occamolab.org)

Static one-page site for OccamoLab, served by GitHub Pages from the `main` branch.

## Files

- `index.html` — the page.
- `style.css` — styles, responsive and dark-mode aware.
- `logo.png` — OccamoLab logo (also used as favicon).
- `CNAME` — custom domain `occamolab.org`.
- `robots.txt`, `sitemap.xml` — crawler metadata.
- `404.html` — fallback page.

## GitHub Pages

1. Repository: `occamolab/occamolab.github.io`.
2. Settings → Pages → Source: **Deploy from a branch**, branch `main`, folder `/ (root)`.
3. Custom domain: `occamolab.org`.
4. After DNS resolves, enable **Enforce HTTPS**.

## DNS at Porkbun

Apex `occamolab.org`:

```
A     185.199.108.153
A     185.199.109.153
A     185.199.110.153
A     185.199.111.153
AAAA  2606:50c0:8000::153
AAAA  2606:50c0:8001::153
AAAA  2606:50c0:8002::153
AAAA  2606:50c0:8003::153
```

`www`:

```
CNAME  occamolab.github.io
```

Email forwarding (Porkbun or Cloudflare Email Routing):

```
hello@occamolab.org  ->  <your Gmail address>
```
