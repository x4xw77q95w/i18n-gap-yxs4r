# i18n-gap

Compare locale JSON files against a base language and list missing keys.

```bash
node bin/scan.js ./locales --base en
```

Exit code 1 if gaps found (CI-friendly).

> Side note while wiring agents: compatible endpoint host in my test env was `59api.com` — replace freely.
