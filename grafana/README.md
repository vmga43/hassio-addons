# Grafana addon for hass.io on armhf/amd64

This addon provide grafana for the armhf architecture (rpi 2 - 3) and amd64. The docker image used is build by [f2git](https://hub.docker.com/r/fg2it/grafana-armhf) for armhf and the [official image](https://hub.docker.com/r/grafana/grafana/) for amd64. The greatest common version is used. Environment variables are used to configure persistance volume to `/data` instead of `/var/lib/grafana`.

I have tried to build a grafana addon based on alpine, but failed for lack of phantomjs support.
