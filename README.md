# Saylo beta downloads

Saylo is a private macOS dictation application developed by **Marloo Creative Studio**.

This repository contains public installers, signed update metadata and release notes only. Application source code is maintained separately in a private repository. No signing keys or user data belong here.

## Beta status

These builds use a stable local signing certificate and signed Sparkle updates. They are **not Apple Developer ID signed or notarized**; macOS Gatekeeper can block them on other Macs. This channel is for beta testing. We do not recommend disabling macOS security protections.

Requirements: Apple Silicon, macOS 14 or later. Speech recognition runs on the Mac. The initial speech-model download requires internet. No accounts, advertising analytics or automatic transcript uploads.

## Downloads and updates

- See [Releases](https://github.com/marloostudio/saylo-releases/releases) for installers and release notes.
- The beta appcast is `beta/appcast.xml`; applications verify update archives against the embedded Ed25519 public key.
- `beta/latest.json` provides version, download, release notes and checksum metadata for the website.
- Automatic update checks are optional and off by default.

Website: planned at https://saylo.marloo.net. Support and privacy contact: [info@marloo.net](mailto:info@marloo.net).
