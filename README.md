# OTUS-CPP-W1-CI

[![Build Status](https://travis-ci.org/olpotkin/OTUS-CPP-W1-CI.svg?branch=master)](https://travis-ci.org/olpotkin/OTUS-CPP-W1-CI)

## Environment
- `docker pull ubuntu:trusty`

## Setup instructions
- `echo "deb https://dl.bintray.com/olpotkin/OTUS-CPP-COURSE trusty main" | sudo tee -a /etc/apt/sources.list`
- `apt update && apt install -y helloworld`

In case of the error "<i>The method driver /usr/lib/apt/methods/https could not be found.</i>":
- `cd /usr/lib/apt/methods`
- `ln -s http https`
