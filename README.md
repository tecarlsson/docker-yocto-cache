# nginx cache server

Adhoc nginx cache server for our yocto build process.

Mount the folder you want to expose at /usr/share/nginx/html/cache.
Logs can be found in /var/log/nginx/.

```
docker run -v /cache/folder/:/usr/share/nginx/html/cache -p 80:80 -d tecarlsson/docker-yocto-cache
```
