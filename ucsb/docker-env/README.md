# Purpose
Test code changes to Primo view using [ExLibrisGroup/primo-explore-devenv](https://github.com/ExLibrisGroup/primo-explore-devenv).

Requirements:
- docker
- docker compose (included in Docker Desktop)

To use this repo:
1. run `docker compose build`
2. run `docker compose up`
3. open a web browser and navigate to `localhost:8003/discovery/search?vid=01UCSB_INST:UCSB`

# Notes
- See [normalization rules](https://github.com/ucsb/library-primo-ve-normalization) for mapping MARC metadata to records displayed in catalog.

# Credit
[thatbudakguy](https://github.com/thatbudakguy/primo-explore-devenv-docker) for the Dockerfile.
