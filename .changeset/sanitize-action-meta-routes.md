---
"@next-community/adapter-vercel": patch
---

Percent-encode server-action meta route transform args that sit outside the API charset, and drop extra action meta routes so the CDN table stays under 2048. ASCII names are unchanged; non-action routes are never dropped.
