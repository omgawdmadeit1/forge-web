# forge.lvlltd.com

Site is published from the `gh-pages` branch of this repo (GitHub Pages).

## Cloudflare DNS (grey-cloud / DNS only, same as DropAgent)

Add a **CNAME** (or A records) for `forge`:

| Type | Name | Content |
| --- | --- | --- |
| CNAME | forge | omgawdmadeit1.github.io |

Or A records to GitHub Pages:

- 185.199.108.153
- 185.199.109.153
- 185.199.110.153
- 185.199.111.153

Then in Cloudflare: **grey cloud** (DNS only) so GitHub can issue HTTPS, or wait for GitHub custom domain cert after proxy.

## Verify

https://forge.lvlltd.com/ should serve Hu-ManForge (Train · Log · Read).

Repo pages settings: https://github.com/omgawdmadeit1/forge-web/settings/pages
