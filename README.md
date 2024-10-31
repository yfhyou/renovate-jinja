# 32252

Currently I have the following image strings in my docker-compose file:
```
    image: traefik:v3.1.6@sha256:f703a2ac2ddf75f6e06c9cccac7f158765e2ab42d642b04e79e2e3d7355c2ddc

    image: litetex/ghcr.gethomepage.homepage:v0.9.11

    image: hotio/sabnzbd:release-4.3.3

    image: hotio/readarr:testing-0.4.2.2653

    image: advplyr/audiobookshelf:2.16.0

    image: hotio/jackett:release-0.22.856
```

I used the below regex to clean up the release, testing and just show the version number. Not sure what the exact issue is as the only issue appears as the warning below. Perhaps I need to make individual 
## Current behavior
Renovate gives the following error:

`WARN: Error updating branch: update failure (branch="renovate/docker-templates")`

## Expected behavior

Renovate should provide the updates to the docker image versions

## Link to the Renovate issue or Discussion

https://github.com/renovatebot/renovate/discussions/32252
