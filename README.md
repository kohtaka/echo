# echo

## A simple tcp echo server written in Dart

[![Build Status](https://drone.io/github.com/kohtaka/echo/status.png)](https://drone.io/github.com/kohtaka/echo/latest)

## Documentation

[http://kohtaka.org/echo/](http://kohtaka.org/echo/)

## How to setup

```bash
$ pub install
```

## How to execute from CLI

```bash
$ ./bin/echo
```

## How to test sources

```bash
$ dart --checked ./tool/hop_runner.dart test
```

## How to analyze sources (statically)

```bash
$ dart --checked ./tool/hop_runner.dart analyze
```

## How to generate documents

```bash
$ dart --checked ./tool/hop_runner.dart docs
```

