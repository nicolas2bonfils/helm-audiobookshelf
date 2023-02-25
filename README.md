# Audiobookshelf

An Helm chart to deploy [Audiobookshelf](https://www.audiobookshelf.org)

## Goal

This repo contains an helm chart to help deploying Audiobookshelf on Kubernetes cluster.

## Installation

Currently that helm-chart is not (yet) deployed to a helm-registry. So you have to install it by checking out this repo

```
$ git checkout https://github.com/nicolas2bonfils/helm-audiobookshelf.git
$ cd helm-audiobookshelf
$ helm install -n audiobookshelf audiobookshelf . -f values.yml
```
