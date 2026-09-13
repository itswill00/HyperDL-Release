# HyperDL Releases & OTA Distribution

Official public release channel and Over-The-Air (OTA) hot-patch distribution for **HyperDL**.

## Latest Release: v1.3.19 (b13190)

- **Standalone Package (Full Module)**: [`HyperDL-v1.3.19.zip`](https://github.com/itswill00/HyperDL-Release/releases/download/v1.3.19/HyperDL-v1.3.19.zip) (~44M)
  - Flashable in Magisk, KernelSU, or APatch.
  - Bundles isolated Bionic Python 3.14 runtime and hardware-accelerated FFmpeg.

- **Lightweight OTA Hot-Patch**: [`HyperDL-OTA-v1.3.19.zip`](https://github.com/itswill00/HyperDL-Release/releases/download/v1.3.19/HyperDL-OTA-v1.3.19.zip) (~184K)
  - Fast in-app update via HyperDL WebUI (~250 KB).
  - Updates logic bundle, native bridge, clipboard daemon, and WebUI without rebooting.

## OTA Metadata Endpoint
- JSON: `https://raw.githubusercontent.com/itswill00/HyperDL-Release/main/update.json`
