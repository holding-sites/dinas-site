# DINAS CONSULTING LIMITED

Corporate website for DINAS CONSULTING LIMITED (Mauritius).

## Hosting

The site is hosted on [GitHub Pages](https://pages.github.com/). Static files in this repository are served automatically.

**Live URL:** https://holding-sites.github.io/dinas-site/

## Custom domain

To connect your own domain (e.g. `dinasconsult.pro`):

1. Add a `CNAME` file to this repository with your domain name
2. Configure a CNAME DNS record at your domain registrar pointing to `holding-sites.github.io`
3. GitHub will provision HTTPS automatically (may take up to 24 hours)

See [GitHub Pages custom domain docs](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site) for details.

## Updating the site

Replace the static files in this repository with a new build from the source project:

```bash
# In the source project (holding-sites/sites/dinas/)
npm run build

# Copy output to this repository
cp -R out/* /path/to/dinas-site/
git add -A && git commit -m "Update site" && git push
```

Changes go live within 1-2 minutes after push.
