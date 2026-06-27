# Squish — macOS Video Shrinker

Drag a video in, pick a format and a target file size, and Squish two-pass
encodes it down to hit that size — with a corrective pass if it overshoots —
then exports the result and reveals it in Finder. A small, single-file desktop
utility for Apple Silicon Macs.

Built with **Tauri v2 + SvelteKit + TypeScript**, with a bundled **ffmpeg**
sidecar doing the real compression.

## Requirements

- macOS on **Apple Silicon** (arm64). This build is arm64-only and unsigned.
