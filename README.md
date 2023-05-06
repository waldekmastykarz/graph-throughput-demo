# Microsoft Graph API error simulations

## MPA

### macOS

- `npx lite-server`
- uncomment scenario in `index.html`
- `mgdp -c msgraph-429.json` or `mgdp -c msgraph-rate-limiting.json`
- `/Applications/Google\ Chrome.app/Contents/MacOS/Google\ Chrome --proxy-server="http://localhost:8000"`
