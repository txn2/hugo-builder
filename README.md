# Container with Hugo

You know, for building static sites in a CI pipeline.

Docker example interactive:

```bash
docker run -it --rm -v $(pwd):/app -w /app txn2/hugo-builder:hugo-0.40.3 sh
```

Docker example build:

```bash
docker run -it --rm -v $(pwd):/app -w /app txn2/hugo-builder:hugo-0.40.3 hugo
```