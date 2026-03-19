# ScriptureTime Releases

This repository hosts public release artifacts for ScriptureTime.

It is intended for:

- OTA manifest files such as `versions.json`, `stable.json`, and `beta.json`
- Published firmware binaries used by deployed devices
- Release metadata needed for update checks

This repository is not the source code repository for ScriptureTime.

## Purpose

The main ScriptureTime source repository remains private. This public repository
exists so devices can download update metadata and firmware binaries without
requiring GitHub authentication.

## Contents

Typical contents include:

- `release/ota/versions.json`
- `release/ota/stable.json`
- `release/ota/beta.json`
- GitHub Release assets such as `ScriptureTime-1.0.0.bin`

## Distribution Notice

The files in this repository are provided for ScriptureTime device update and
distribution purposes only. Except where third-party components require
otherwise, no permission is granted to copy, modify, redistribute, or create
derivative works from these artifacts.

See `LICENSE` for repository terms.
