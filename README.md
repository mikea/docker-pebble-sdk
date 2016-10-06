# docker-pebble-sdk

[![CircleCI](https://circleci.com/gh/mikea/docker-pebble-sdk.svg?style=svg)](https://circleci.com/gh/mikea/docker-pebble-sdk)

Docker image for Pebble SDK


## LEGAL NOTE
You must accept the [Pebble Terms of Use][TOS] and the [SDK License Agreement][LA] to use the Pebble SDK and to build this image.

[TOS]: https://developer.getpebble.com/legal/terms-of-use/
[LA]: https://developer.getpebble.com/legal/sdk-license/

## Building Image

Assuming that you *have* accepted the above:

```bash
docker build -t docker-pebble-sdk .
```
## Building App

From app directory:

```bash
docker run --rm -ti -v $PWD:/pebble docker-pebble-sdk pebble compile
```
