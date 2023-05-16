# Alpine Linux Package
Uptycs Package for Linux Alpine

## File Hash
SHA256: 81302907a56e22506918c87428c9a43fa46dd1e43c8ca746b7d154f6c331746f

## Installing the Agent

1) Download the flags, secret, and cert (osquery.flags, uptycs.secret, ca.crt)files from your Uptycs tenant and copy them to /etc/osquery 

2) Install as root using the command: 
```
sudo apk add --allow-untrusted /path/to/osquery-<version>.apk
```

After installation the osquery service should automatically start
