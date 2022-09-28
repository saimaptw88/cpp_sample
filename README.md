## Overview

cpp sample program based on docker & cmake

## Tools

- docker -v: 20.10.13
- docker-compose -v: 1.29.2

## Usage

### Initial settings

- `docker-compose build`
- `docker-compose run dev bash`

### Build

- `docker-compose up -d`
- `docker-compose exec dev cmake ..`
- `docker-compose exec dev cmake --build .`
- `docker-compose exec dev ./my_app`

## Lint(CppLint)
- `docker-compose exec dev cpplint ../hello.cpp ../hello.h ../main.cpp`

## References

- [c++ with docker](https://qiita.com/kai_kou/items/1f4b9a45a5d4d6788649)
- [coenvl/googletest
](https://hub.docker.com/r/coenvl/googletest/dockerfile)
