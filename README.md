# .tentacle

This repository contains the global configuration which defines default for [Tentacle](https://tentacle.app/) within your GitHub organizations. 

## How it works

Tentacle will attempt to load the global configuration defined in `<org>/.tentacle/global.yml` and then the repository config from `<org>/my-repo/.github/tentacle.yml`. Tentacle will then merge both configs into one.
