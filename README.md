# golang-dep-playground

project to learn to use [dep](https://golang.github.io/dep/) the dependency management tool for [go](https://golang.org/)

```sh
# create new project
dep init

# add new import(s) in source code

# pull down imports into ./vendor/
dep ensure

# can always run `dep ensure` to sync everything up
```