# Lanora releases

Public downloads for Lanora, a private virtual LAN for gaming rooms.

## Downloads

Get installers, release notes, and SHA-256 checksums from [Releases](https://github.com/snikolchikov/lanora-releases/releases).

Release targets:

- Windows 11 x64 — `.exe` installer.
- Linux Mint 22.x / Ubuntu 24.04 amd64 — `.deb` package.

macOS support is experimental and is not included in these releases yet.
Prereleases are test builds; consult each release’s notes for validation status and limitations.

## Verify downloads

Each release includes `SHA256SUMS.txt` and `manifest.json` with the version, source revision, platform, download URL, and SHA-256 of each installer.

On Linux, download both installers, the manifest, and checksums into the same directory and run `sha256sum --check SHA256SUMS.txt`.
On Windows, use `Get-FileHash .\Lanora-Windows-x64.exe -Algorithm SHA256` and compare the result with `SHA256SUMS.txt`.

## Website links

Versioned downloads use `/releases/download/<tag>/<asset-name>`.
The latest stable downloads use `/releases/latest/download/<asset-name>`.
Installer asset names are `Lanora-Windows-x64.exe` and `Lanora-Linux-amd64.deb`.
These links become available once the corresponding release has been published.

## Repository contents

This repository distributes installers, checksums, manifests, and release notes. Application development and source code are maintained separately in a private repository.
