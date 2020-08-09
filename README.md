<p align="center"><a href="#readme"><img src="https://gh.kaos.st/go-jar.svg"/></a></p>

<p align="center">
  <a href="https://pkg.go.dev/github.com/essentialkaos/go-jar"><img src="https://pkg.go.dev/badge/github.com/essentialkaos/go-jar"></a>
  <a href="https://goreportcard.com/report/github.com/essentialkaos/go-jar"><img src="https://goreportcard.com/badge/github.com/essentialkaos/go-jar"></a>
  <a href="https://travis-ci.com/essentialkaos/go-jar"><img src="https://travis-ci.com/essentialkaos/go-jar.svg"></a>
  <a href="https://github.com/essentialkaos/go-jar/actions?query=workflow%3ACodeQL"><img src="https://github.com/essentialkaos/go-jar/workflows/CodeQL/badge.svg" /></a>
  <a href="https://coveralls.io/github/essentialkaos/go-jar?branch=master"><img src="https://coveralls.io/repos/github/essentialkaos/go-jar/badge.svg?branch=master" alt="Coverage Status" /></a>
  <a href="https://github.com/essentialkaos/go-jar/actions"><img src="https://github.com/essentialkaos/go-jar/workflows/Go/badge.svg" alt="GitHub Actions Status" /></a>
  <a href="https://codebeat.co/projects/github-com-essentialkaos-go-jar-master"><img alt="codebeat badge" src="https://codebeat.co/badges/eafd2393-ab11-4d0e-bdc3-e51613c9e38a" /></a>
  <a href="#license"><img src="https://gh.kaos.st/apache2.svg"></a>
</p>

<p align="center"><a href="#installation">Installation</a> • <a href="#build-status">Build Status</a> • <a href="#license">License</a></p>

<br/>

`jar` is a very simple Go package for reading manifest data from JAR files.

### Installation

Before the initial install allows git to use redirects for [pkg.re](https://github.com/essentialkaos/pkgre) service (_reason why you should do this described [here](https://github.com/essentialkaos/pkgre#git-support)_):

```
git config --global http.https://pkg.re.followRedirects true
```

Make sure you have a working Go 1.12+ workspace (_[instructions](https://golang.org/doc/install)_), then:

```
go get pkg.re/essentialkaos/go-jar.v1
```

For update to the latest stable release, do:

```
go get -u pkg.re/essentialkaos/go-jar.v1
```

### Build Status

| Branch | Status |
|--------|--------|
| `master` | [![Build Status](https://travis-ci.com/essentialkaos/go-jar.svg?branch=master)](https://travis-ci.com/essentialkaos/go-jar) |
| `develop` | [![Build Status](https://travis-ci.com/essentialkaos/go-jar.svg?branch=develop)](https://travis-ci.com/essentialkaos/go-jar) |

### License

[Apache License, Version 2.0](https://www.apache.org/licenses/LICENSE-2.0)

<p align="center"><a href="https://essentialkaos.com"><img src="https://gh.kaos.st/ekgh.svg"/></a></p>
