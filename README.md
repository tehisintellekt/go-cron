go-cron
=========

Simple golang wrapper over `github.com/robfig/cron` and `os/exec` as a cron replacement

## Usage

  go-cron "* * * * * *" /bin/bash -c "echo 1"

## Build

  docker run --rm -v "$(pwd):/go/src/app" -w /go/src/app golang:1.8 ./bin/build
