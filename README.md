# Dockerized

*[Read about it on Medium](https://medium.com/@skibish/how-docker-changed-my-workflow-b953b79b73ff)*

## Motivation

In some cases you do not want to install something directly on your OS, because it can create caches, hidden directories, etc. and you will loose track of it

## Installation

**OS**: Linux

To install:

```bash

git clone https://github.com/ipunkt/dockerized.git $HOME/dockerized

```

And add it to your path in `.<bash|zsh|etc>rc` file:

```bash

# You need to prepend it to path to overwrite what you have in your path
export PATH=$HOME/dockerized/bin:$PATH

# Or, to just add new functionality, add this
export PATH=$PATH:$HOME/dockerized/bin

```

## Supported Commands

### PHP

- php
- composer
- phpunit
- phpco
- phpcs
- phpcbf
- phpmd `phpmd . text cleancode,codesize,controversial,design,naming,unusedcode`

### Node

- node
- npm
- npx
- yarn
- gulp

### Docker

- docker-purge-all
- docker-stop-all
- docker-update-images

### Rancher

- rancherize
- rancherize-latest

### Misc

- http
- gtt
- wizzy
