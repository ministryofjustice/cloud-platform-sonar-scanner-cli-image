# cloud-platform-sonar-scanner-cli-image

A docker image that primarily contains the required packages for running the 'sonar-scanner-cli' tool. 

The image includes:

  - `sonar-scanner-cli`
  - `aws`
  - `git-crypt`
  - `kubectl`
  - `ruby`

## Building and tagging the tools image

A github action builds the tools image and pushes it to [DockerHub](https://hub.docker.com/r/ministryofjustice/cloud-platform-sonar-scanner-cli) whenever a new release is defined in github.

The image is tagged with the release number.