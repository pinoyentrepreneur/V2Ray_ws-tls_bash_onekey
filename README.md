## Vmess+websocket+TLS+Nginx+Website
```
wget -N --no-check-certificate -q -O install.sh "https://raw.githubusercontent.com/pinoyentrepreneur/V2Ray_ws-tls_bash_onekey/master/install.sh" && chmod +x install.sh && bash install.sh
```
 

### Start Command

To Start V2ray：`systemctl start v2ray`

To Stop V2ray：`systemctl stop v2ray`

To Start Nginx：`systemctl start nginx`

To Stop Nginx：`systemctl stop nginx`

### Related directory

Web Root Directory：`/home/wwwroot/3DCEList`

V2ray Server Config：`/etc/v2ray/config.json`

V2ray Client Config: `~/v2ray_info.inf`

Nginx Root Directory： `/etc/nginx`

Cretificate Key : `/data/v2ray.key`

Certificate File : `/data/v2ray.crt`






