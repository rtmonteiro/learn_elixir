# Learning Elixir

## Introduction

## Setup

```bash
docker run -p 8080:8080 -p 8081:8081 --pull always ghcr.io/livebook-dev/livebook
```

```bash
docker run -p 8080:8080 -p 8081:8081 --pull always -u $(id -u):$(id -g) -v $(pwd):/data ghcr.io/livebook-dev/livebook
```
