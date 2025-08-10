# mapbox-api-audit
Audits the permissions given a mapbox API token. 

Usage: `python .\main.py <mapbox_public_token> <username> [--verbose]`

Example output: 

```
[-] Styles API: Forbidden (HTTP 403) — likely restricted
[+] Static Images API: OK (HTTP 200)
[+] Directions API: OK (HTTP 200)
[?] Tiles API: Unexpected status 404
[+] Geocoding API: OK (HTTP 200)
[+] Matrix API: OK (HTTP 200)
[+] Map Matching API: OK (HTTP 200)
[+] Isochrones API: OK (HTTP 200)
[+] Optimization API: OK (HTTP 200)
[+] Uploads API: OK (HTTP 200)
[?] Datasets API: Unexpected status 404
[-] Tilesets API: Forbidden (HTTP 403) — likely restricted
[?] Accounts API: Unexpected status 404
[?] Tokens API: Unexpected status 404
[?] Rate Limits API: Unexpected status 404
```
