# Integrated Firmware

Public firmware files for the `통합 펌웨어` updater.

The updater reads these absolute raw URLs:

- `https://raw.githubusercontent.com/itple-lab/integrated-firmware/main/firmware/unplugged/manifest.json`
- `https://raw.githubusercontent.com/itple-lab/integrated-firmware/main/firmware/app/manifest.json`
- `https://raw.githubusercontent.com/itple-lab/integrated-firmware/main/firmware/coconut/manifest.json`

When replacing a firmware file, update the matching `version` and `checksum` in `manifest.json`.

