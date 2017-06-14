# docker-pyenv - a Docker container for pyenv

# DOCKER HUB

https://registry.hub.docker.com/u/mcandre/docker-pyenv/

# EXAMPLE

```
$ make
docker run --rm mcandre/docker-pyenv:latest pyenv --version
pyenv 20150719-6-g57d1c9d
```

# REQUIREMENTS

* [Docker](https://www.docker.com/)

## Optional

* [make](http://www.gnu.org/software/make/)
* [Node.js](https://nodejs.org/en/) (for dockerlint)
* [editorconfig-cli](https://github.com/amyboyd/editorconfig-cli) (e.g. `go get github.com/amyboyd/editorconfig-cli`)
* [flcl](https://github.com/mcandre/flcl) (e.g. `go get github.com/mcandre/flcl/...`)
