[![CircleCI](https://circleci.com/gh/ram1421/pluralsight-docker-CI-master.svg?style=svg)](https://circleci.com/gh/ram1421/pluralsight-docker-CI-master)

# Test app for Pluralsight course

This is a quick and dirty test node.js app cobbled together for the purposes of demonstrating a basic CI/CD workflow with Docker Hub for a Pluralsight video training course..

## Instructions for use

All of the files included in the .zip file (available to Plus subscribers) should be unzipped into a new directory.

Initializing a Git repo and making a remote of it on GitHub are explained in Module 2 of the course.

The viewer should have Git installed and have a GitHub account.



curl -H "Content-Type:application/json" --data'{"build":true}' -X POST https://registry.hub.docker.com/u/bhargava381/pluralsight-docker-ci-master/trigger/4448853b-626d-4f69-889d-75247edcbc27/
