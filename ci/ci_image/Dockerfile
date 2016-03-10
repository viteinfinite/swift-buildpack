FROM concourse/concourse-ci
# https://github.com/concourse/concourse/blob/master/ci/dockerfiles/concourse-ci/Dockerfile

RUN apt-get update && apt-get install zip unzip curl wget tree -y

# libdispatch
RUN apt-get install autoconf automake libtool libkqueue-dev libkqueue0 libdispatch-dev libdispatch0 libhttp-parser-dev libcurl4-openssl-dev libhiredis-dev libbsd-dev -y
