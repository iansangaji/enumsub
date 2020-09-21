# enumsub
A simple command enumeration subdomain

# crt.sh
```
curl -s "https://crt.sh/?q=sangaji.co&output=json" | jq -r '.[].name_value' | sort -u | httpx --silent -content-length -status-code
```
