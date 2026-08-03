# Rackie™

`v2.0.0`

### Brief
Rackie is a self-hosted server management platform that makes it easy to deploy, manage, and monitor applications on your own hardware. It provides a simple web interface for installing popular services, managing Docker containers, and accessing your applications without requiring extensive Linux or Docker knowledge.

## What's New
### Features
- Added an app browser
- Added ability to install apps from the app browser
- Added ability to open installed apps in an iframe (not all apps will open in the iframe, some may need to be launched in a new window)
- When a new update is available, you can now view the README for that update.
- Added Terms of Service v2.0.0

### Patches
- Updated license activation page
- Updated styling
- Added visual feedback when installing apps
- Removed hard-coded app categories
- App categories are now dynamic based on the categories present in the rackie-manifest.json
- Added app health indicator
- Updated location of Rackie's docker-compose.yml file to /opt/rackie
- Added a new "apps" directory in /opt/rackie to contain a docker-compose.yml file for all apps
- Activating a license now saves the license hash in /opt/rackie/rackie-data/rackie-license-hash.dat
- Updated favicon

### Bug Fixes
- Fixed bug where the app list would not update after installing an app
- Fixed bug where the app list would not update after uninstalling an app

### Added Apps
- glances
- jellyfin
- minecraft
- prowlarr
- qBittorrent
- qui
- uptime-kuma

## Join the Community
Hey everyone, it's Mason, the creator or Rackie. I made a discord server that you can join and ask questions in the community! Here's the link: https://discord.gg/2GPDvEE4w