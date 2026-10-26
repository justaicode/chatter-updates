# Chatter for macOS

[Download Chatter 0.2.78 for macOS](https://github.com/justaicode/chatter-updates/releases/download/v0.2.78/Chatter-0.2.78-macOS.zip) · [Release notes and all assets](https://github.com/justaicode/chatter-updates/releases/tag/v0.2.78)

Requires a Mac with Apple silicon. The app is Developer ID signed and notarized by Apple.

Chatter brings your WhatsApp, Telegram, Instagram, Messenger, Viber and Apple Messages chats into one Mac window. Accounts keep separate local sessions on your Mac.

## Install

1. Download **Chatter-0.2.78-macOS.zip** and open it to expand **Chatter.app**.
2. Quit Chatter if it is already running.
3. Drag **Chatter.app** into **Applications**, replacing the older version when prompted, then open it.

Your accounts, saved history and settings are preserved.

## Updates

Chatter checks this repository for updates when it opens and every six hours. **Automatically download and install updates** is under **Settings → About → Software updates** and is on by default; use **Check for Updates…** there or in the **Help** menu at any time. Updates install when Chatter quits, or right away with **Restart to Update**. Update checks send no account or device identifiers.

Each update is verified before installation: the feed and the archive are signed with Chatter’s Ed25519 update key, the download must match its SHA-256 and size, and the app must pass `codesign --verify --deep --strict` with the same Developer ID team and bundle identifier as the installed app. Older or equal versions are never installed.

This repository contains public release archives and the signed update feed (`chatter-update.json`, attached to each release). Application source remains private. Do not edit release feeds after signing.
