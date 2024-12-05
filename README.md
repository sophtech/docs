# Soph Documentation

### Setup

Bulid the docker image

```
docker build -t docs:latest -f Dockerfile .
```

Run the docker image

```
docker run -v .:/unify-docs -p 3000:3000 docs:latest
```

The docs should be live at localhost:3000.

#### Restart

```
docker restart <container-id>
```