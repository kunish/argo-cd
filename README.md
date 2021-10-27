## Argo CD Homelab Playground

### How to use it

```shell
kubectl apply -f project.yml -f application.yml
```

### Features

- Syncs application desired state with description manifest
- Triggers new sync action when there's a new push

### Available Sites

- [Personal Website](https://stack.shikun.info)
- [Whoami (a simple http request testing backend)](https://whoami.shikun.info)

### TODO

- [ ] deploy with kustomize
- [ ] deploy with helm
