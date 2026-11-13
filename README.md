# S + J Almanac — updates & notes

This repository delivers two things to one small seasonal display:

- **Firmware updates.** Releases contain `firmware.bin` and `manifest.json`. The device checks the latest release once a night while its screen is off, verifies the ECDSA P-256 signature, installs it and reboots.
- **Notes.** `mailbox.json` holds short notes encrypted with AES-256-GCM. Only the device (and its owner) holds the key. The page in `docs/` writes notes from a phone.

No source code, Wi-Fi details or keys live here.
