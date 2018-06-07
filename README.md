# docker-ci-rails
Docker image to plug in Gitlab CI for testing rails apps

The image is located at https://hub.docker.com/r/simplicity/ci-rails/

## Usage
You can get the image using
    
    docker pull simplicity/ci-rails

Or in your ```.gitlab-ci.yml``` file:

    image: "simplicity/ci-rails:ruby-2.2"

## Building & Pushing

    docker build -t REPO/ci-rails:ruby-VERSION
    docker push REPO/ci-rails:ruby-VERSION