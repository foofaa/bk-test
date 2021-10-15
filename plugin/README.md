# Lint
```sh
docker-compose run --rm lint
```

# Example
Add the folloing to your pipeline.yml:
```yml
steps:
  - command: ls
    plugins:
    - foo/file-counter#v1.0.0:
      pattern: '*.yml'
```
