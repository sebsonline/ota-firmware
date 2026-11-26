# ota-firmware

Compiled firmware builds for my ESP32 boards. Each device has one release (named after the
device) holding its recent builds and a `manifest.json` that points at the current one.
Boards check their manifest and update themselves over Wi-Fi.

Binaries only. No credentials are stored in these files.
