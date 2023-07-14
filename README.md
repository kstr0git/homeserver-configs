# My homeserver config
This repo contains various docker-compose files that are currently running on my home lab. This is mostly just for my own personal use but if you find anything useful I hope it helps!
- `homer` - A custom static homepage/dashboard configured with a simple yml file.
- `jellyfin` - A clean home media server.
- `nextcloud` - A self hosted cloud storage alternative to Google Drive or 365 with integrated apps.
- `syncthing` - A peer-to-peer file synchronization application which I use to sync files between my phone, server and desktop on my local network.
- `uptime-kuma` - A monitoring tool I used to notify me of outages and check the status of my docker containers. ([status page](https://monitor.kierstro.xyz/status/up)).
- `watchtower` - Scans for changes to docker images and automatically recreates containers when it detects an update.
- `gluetun` - A lightweight and feature packed VPN client for VPN multiple service providers.
- `qbittorrent` - A bitTorrent client running through VPN (relies on gluetun)
