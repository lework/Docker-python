# Docker-python
![docker hub](https://img.shields.io/docker/pulls/lework/python.svg?style=flat-square)
![docker hub](https://img.shields.io/docker/stars/lework/python.svg?style=flat-square)
基于python-alpine基础镜像的python环境


## Versioning
| Docker Tag | Git Release | Python Version |
|-----|-------|-----|
| latest/3.7.3-alpine3.10 | Master Branch |3.7.3 |
| 3.7.3-alpine3.10 | 3.7.3-alpine3.10 |3.7.3 |


## Quick Start

```
docker run -tid -v /opt/django:/src -p 80:80 lework/python:latest
```