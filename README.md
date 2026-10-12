# Redirect stefanodagogle.com → stefanosuperina.it

Repository dedicato ai redirect dal vecchio dominio al nuovo.

- **CNAME**: `stefanodagogle.com`
- `index.html` e `404.html` reindirizzano preservando path, query e hash.

## Setup GitHub Pages
1. Settings → Pages → Source: Deploy from branch `main` / root
2. Custom domain: `stefanodagogle.com` (Enforce HTTPS)
3. DNS già punta agli IP GitHub + www CNAME → stefanosupernet-sudo.github.io
