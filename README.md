# Daft Backstage

Daft Backstage is the macOS companion app for [Daft Music](https://daftmusic.app). It captures
Daft Music's audio and renders it to the output device you pick, so the app can do things a
sandboxed music player cannot do on its own:

- **Stream to other devices.** AirPlay speakers, headphones and any Core Audio output device.
- **Equalizer.** Shape the sound before it reaches the device.
- **Instrument isolation.** Bring the vocals, drums or bass forward, or take them out.

Backstage is optional. Daft Music plays fine without it, and it only handles audio coming from
Daft Music itself.

## Requirements

- macOS 26.4 or later
- Daft Music

## Install

Download the latest `DaftBackstage.dmg` from [Releases](../../releases), open it and drag the app
to your Applications folder. Launch it once and Daft Music picks it up from there. It runs in the
menu bar and starts with your Mac.

The app is signed with a Developer ID and notarized by Apple. It is distributed here rather than
on the App Store because capturing system audio is not something a sandboxed app is allowed to do.

## Updating

Daft Music tells you when a new version is out and links back here. Install the new build over the
old one; nothing else to do.

## Issues

This repository is for distributing releases. For bugs and feedback, use
[Issues](../../issues).
