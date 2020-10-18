# sample-scheduler-framework

This repo is a sample for Kubernetes scheduler framework.

For a fresh cloned repo, run `go mod vendor` and `GOOS=linux GOARCH=amd64 go build -o sample-scheduler-framework *.go` to compile the main binary.

## Deploy

```shell
$ kubectl apply -f deploy/sample-scheduler.yaml
```

## Test
```shell
$ kubectl apply -f deploy/test-scheduler.yaml
```

Then watch sample-scheduler pod logs.
