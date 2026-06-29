# skvault-skworld-io

Landing site for **skvault** — the sovereign secrets vault — served at
**[skvault.skworld.io](https://skvault.skworld.io)** via GitHub Pages.

skvault is a KeePass-backed secrets vault whose master key is PGP-sealed to your sovereign
identity and unlocked into gpg-agent. It was split out of skingest (EPIC `11eeac9e`), depends
on `capauth.seal`, and is reached through one stable shim (`~/.skenv/bin/skvault`). The vault
never holds your master.

- **Product repo:** https://github.com/smilinTux/skvault
- **Crypto home:** https://github.com/smilinTux/capauth
- **Ingestion sibling:** https://github.com/smilinTux/skingest

## Files

| File | Purpose |
|------|---------|
| `index.html` | The single-page landing site (self-contained CSS/JS) |
| `CNAME` | GitHub Pages custom domain → `skvault.skworld.io` |
| `robots.txt` | AI-crawler-friendly robots + content signals |
| `sitemap.xml` | Sitemap |
| `llms.txt` | Machine-readable summary for LLMs |

Built to the SKWorld Site Standard — mirrors the `skos-skworld-io` pattern and the shared
SEO/og templates. GPL-3.0.
