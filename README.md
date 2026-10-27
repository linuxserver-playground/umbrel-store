# LinuxServer.io Umbrel community app store

**This repository is generated.** Every file is written by the [hub](https://github.com/linuxserver-playground/hub) from each image's `image.yml`
and newest build, and pushed by its hourly refresh workflow; edits here are overwritten by the next run. Changes belong in
the image's repository (its `image.yml`) or in the hub's `lsio_hub/generate/umbrel.py`.

## Import

In umbrelOS open the App Store, choose *Community App Stores* and add `https://github.com/linuxserver-playground/umbrel-store`.

## Layout

`umbrel-app-store.yml` (store id `lsio`) and one `lsio-<app>/` directory per image with `umbrel-app.yml` and `docker-compose.yml`.

The same output is served at `https://linuxserver-playground.github.io/hub/stores/umbrel/`; the store index
with every platform is `https://linuxserver-playground.github.io/hub/api/v1/stores/index.json`.
