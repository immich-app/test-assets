# Test assets for Immich

This repository contains assets primarily used for end-to-end testing the self-hosted open-source photo manager [Immich](https://immich.app/). The goal is to have a set of photos and videos that cover a wide range of use cases and edge cases. All assets are public domain, and attempts are made to keep file sizes manageable.

# File formats

The goal is to eventually cover [all formats supported by Immich](https://github.com/immich-app/immich/blob/9bada51d56aeaf4929b683078600655dfbdc7216/server/src/domain/domain.constant.ts#L26). This includes raw formats of a wide range of cameras, as well as live photos and video formats. The following formats are currently included:

- JPEG
- HEIC
- PNG

The following raw formats are currently included:

- NEF (Nikon D80)
- NEF (Nikon D700)

We also aim to include sidecar metadata files.
