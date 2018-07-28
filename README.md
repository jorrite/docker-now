# docker-now

## Purpose

This image was created specifically for usage with continuous integration
systems, and contains the minimum requirements to deploy a project to
[Now](https://zeit.co/now). Currently being used with
[GitLab CI](https://about.gitlab.com/features/gitlab-ci-cd/), but should meet the requirements for most CI
systems.

## Details

### Base Image

* [node (carbon)](https://hub.docker.com/r/library/node/) - The latest Node LTS
  (Carbon) image

### Additional Node Modules

* [Now CLI](https://zeit.co/now) - Now Command
  Line Tools. Required to deploy to now.
