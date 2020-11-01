# Motivation

Debugging Github Actions (or any CI) is annoying if you can't run it locally.

_act_ let's you run them locally.

# Usage

## Install ACT

1. See https://github.com/nektos/act
2. You also need Docker.

## Run locally with ACT

```shell
act -P ubuntu-latest=nektos/act-environments-ubuntu:18.04
```

- Tip: Use `-v` if there's some error.
