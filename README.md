# QA test repo — docker-compose under docker/ subdirectory

Used to verify xCloud PR #7237 (per-site Compose project pin, fixes #7236):
https://github.com/xCloudDev/xCloud/pull/7237

Compose file lives at `docker/docker-compose.yml` — this is the exact
directory shape that collided with any other site using the same layout
before the fix (both would resolve to Compose project `docker`).
