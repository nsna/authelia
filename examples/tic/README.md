Requires the following hosts entries for localhost testing:

```
127.0.0.1 dev.internal
127.0.0.1 auth.dev.internal
127.0.0.1 test.dev.internal
```

Build the docker image:
```
docker build -t authelia -f Dockerfile.dev .
```

Run the compose file to bring up local testing:
```
docker compose up -d
```

Configuration file not committed due to requiring secrets.
