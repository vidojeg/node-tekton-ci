# node-tekton-ci

Build node app

## Pipeline requirement

- Kubernetes >= 1.25
- Tekton >= v0.41.0
- Sealed secrets

## Pipeline Inputs

- GIT APP REPO
- APP REVISION
- NPM ARGS

## Pipeline Tasks

- git-clone
- npm
- sonar

