# Mumble release

This is a [mumble server](https://www.mumble.com/) also called murmur boshrelease. This let you deploy a mumble server through bosh.

## Usage

1. use manifest at [/manifests/mumble.yml](/manifests/mumble.yml) with `bosh -d mumble deploy ./manifests/mumble.yml`
2. This is over you have a new mumble, password can be found by using credhub cli