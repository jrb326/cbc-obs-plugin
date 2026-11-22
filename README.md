# CBC OBS Plugin

Native OBS plugin for local multi-RTMP encoding and fan-out, plus auto-spawning the CBC dock panel inside OBS.

## Overview

- **C++ / CMake / Qt** — native OBS plugin.
- **Multi-RTMP encoding / fan-out** — encode once locally and publish to multiple RTMP destinations.
- **Embedded dock** — launches the `apps/docks` web panel inside OBS.

## Alternative

Cloud-side restreaming can replace this plugin entirely; the plugin exists for local, on-machine fan-out.

## License

GPLv2.

## Related repositories

- [cbc-platform](https://git.mcsprig.dev/x1xx/cbc-platform) — main monorepo (contains `apps/docks`).
- [cbc-showcase](https://git.mcsprig.dev/x1xx/cbc-showcase) — public portfolio and system diagrams.
