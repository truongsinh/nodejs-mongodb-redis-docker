
# NodeJS

This creates an image which contains an environment for NodeJS app ecosystem

- Node.js 0.10.23
- MongoDB 2.4.8
- Redis 2.4.15

This image can be used as a standalone, or a base image for others.

## Usage

Standalone
```sh
docker run -i -t truongsinh/nodejs-mongodb-redis
```

Based image for other builds

```
#…

FROM truongsinh/nodejs-mongodb-redis

#…
```
