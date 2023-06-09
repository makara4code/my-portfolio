# Deployment Step

Make sure you remove dist from .gitignore file

## Build the project

```code
  pnpm build
  npm build
  yarn buil
```

## Commit the code

```bash
$ git add .
$ git commit -m "message"
$ git push
$ git subtree push --prefix dist origin gh-pages
```
