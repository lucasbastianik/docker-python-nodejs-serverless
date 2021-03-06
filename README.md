[![Travis](https://img.shields.io/travis/lucasbastianik/docker-python-nodejs-serverless.svg?style=flat-square)](https://travis-ci.org/lucasbastianik/docker-python-nodejs-serverless)
[![Pulls](https://img.shields.io/docker/pulls/lucasbastianik/python-nodejs-serverless.svg?style=flat-square)](https://hub.docker.com/r/lucasbastianik/python-nodejs-serverless/)
![](https://img.shields.io/microbadger/image-size/lucasbastianik/python-nodejs-serverless.svg)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Python (latest) with Node.js 10.x and Serverless Framework based on [nikolaik/docker-python-nodejs](https://github.com/nikolaik/docker-python-nodejs)
- Node: 10.x
- npm: 6.x
- serverless: latest
- yarn: stable
- Python: latest
- pip: latest
- pipenv: latest

----
### Pull from Docker Hub
```
docker pull lucasbastianik/python-nodejs-serverless:latest
```

### Build from GitHub
```
docker build -t lucasbastianik/python-nodejs-serverless github.com/lucasbastianik/docker-python-nodejs-serverless
```

### Run image
```
docker run -it lucasbastianik/python-nodejs-serverless bash
```

### Use as base image
```Dockerfile
FROM lucasbastianik/python-nodejs-serverless:latest
```

## Disclaimer
> This is experimental and might break from time to time. Use at your own risk!
