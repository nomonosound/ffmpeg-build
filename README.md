Static audio-only FFmpeg builds
===============================

This project contains scripts for small static audio-only FFmpeg builds that are used
for some of Nomono's software.

Building is done using GitHub Actions. You can find the built binaries on the releases page.

Supported platforms:

  - Linux
      * `x86\_64-linux-gnu`
  - Windows
      * `x86\_64-w64-mingw32`
  - macOS
      * `x86_64-apple-macos10.9` (macOS Mavericks and newer on Intel CPU)
      * `arm64-apple-macos11` (macOS Big Sur and newer on Apple M1 CPU)

## Tag naming scheme

For example, the first custom build of ffmpeg 5.1.2 would be tagged with name `v5.1.2-nomono-audio-v1`

## Motivation

Small binaries
