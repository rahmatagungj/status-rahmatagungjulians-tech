# status-rahmatagungjulians-tech
Monitoring for my all services and sites

## Run Production
```
sudo docker-compose up -d
```

### NginX Config
```
proxy_set_header   Upgrade $http_upgrade;
proxy_set_header   Connection "upgrade";
```
more info [NginX Reverse Proxy](https://github.com/louislam/uptime-kuma/wiki/Reverse-Proxy#nginx)
