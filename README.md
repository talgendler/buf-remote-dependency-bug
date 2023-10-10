# Repo to reproduce a bug: https://github.com/bufbuild/buf/issues/2480


To reproduce use `buf@v1.27.0`

```shell
buf lint ssh://git@github.com/talgendler/buf-remote-dependency-bug.git#branch=main,subdir=service --path service/service/private/v1/private.proto
```

