# HOW TO

## Run it first

```
openssl rand -base64 756 > mongo-keyfile
chmod 400 mongo-keyfile
```

## Add it to your hosts

```
127.0.0.1 mongo-rs0-1
127.0.0.1 mongo-rs0-2
127.0.0.1 mongo-rs0-3
```
