# Instruction for Nginx image filter

## Add to /etc/apt/sources.list for Ubuntu focal

```bash
deb http://nginx.org/packages/ubuntu/ focal nginx
```

## Add repository GPG key

```bash
wget https://nginx.org/keys/nginx_signing.key && sudo apt-key add nginx_signing.key
```

## Install nginx-module-image-filter

```bash
sudo apt-get install nginx-module-image-filter
```

## Reload nginx

```bash
sudo systemctl reload nginx
```
