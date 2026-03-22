# Hardware Founder Guide

**Live:** https://www.hardwarefounderguide.com

The complete guide to taking a hardware product from idea to mass production.
Part of the Hans Stam hardware ecosystem.

## Files
- `index.html` — The guide (single page)
- `CNAME` — Custom domain for GitHub Pages
- `robots.txt` — SEO
- `sitemap.xml` — SEO

## GitHub Pages + GoDaddy DNS Setup

### GitHub
1. Create repo: `hansstam86/hardwarefounderguide.com`
2. Upload all files
3. Settings → Pages → Source: main branch, root
4. Custom domain: `www.hardwarefounderguide.com`
5. Enforce HTTPS: ✓

### GoDaddy DNS
| Type  | Name | Value                    |
|-------|------|--------------------------|
| A     | @    | 185.199.108.153          |
| A     | @    | 185.199.109.153          |
| A     | @    | 185.199.110.153          |
| A     | @    | 185.199.111.153          |
| CNAME | www  | hansstam86.github.io     |

DNS propagation takes 10–30 minutes.
