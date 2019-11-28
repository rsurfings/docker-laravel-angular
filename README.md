#docker laravel angular

## build && Running
```
docker-compose build --no-cache && docker-compose up -d
```

You can easily tweak the nginx config in deploy

Frontend[Angular] app will be available at http://localhost
nginx config at	deploy/client.docker

Backend[Laravel] at http://localhost:8080
nginx config at	deploy/vhost.conf

