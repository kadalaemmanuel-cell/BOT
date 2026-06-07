# Roylon Bot

Roylon Bot is a WhatsApp bot built with the Baileys library for group management, moderation, fun commands, downloads, stickers, games, and AI-style tools.

## Features

- Tag all group members with `.tagall`
- Group admin tools like mute, unmute, promote, demote, kick, warn, and reset warnings
- Anti-link, anti-tag, anti-badword, anti-delete, anti-call, and PM blocker controls
- Welcome and goodbye messages
- Sticker and image tools
- Text-to-speech with `.tts`
- Games like Tic-Tac-Toe, Hangman, Trivia, Truth, and Dare
- Downloader commands for music, video, Instagram, Facebook, TikTok, and Spotify

## Owner

- Bot name: Roylon Bot
- Owner: Kdealer
- Owner number: 2348100996979
- Repository: https://github.com/kadalaemmanuel-cell/BOT

## Setup

### Prerequisites

- Node.js 20 or newer
- Git
- A WhatsApp account you understand may be at risk when using unofficial automation

### Install

```bash
git clone https://github.com/kadalaemmanuel-cell/BOT.git
cd BOT
npm install
```

### Run

```bash
npm start
```

The bot stores WhatsApp session files in the `session` folder. Keep that folder private.

## Environment Variables

API keys should be provided through environment variables instead of being committed to the repo.

Supported variables:

```bash
GIPHY_API_KEY=
XTEAM_API_KEY=
LOLHUMAN_API_KEY=
NEOXR_API_KEY=
VIOLETICS_API_KEY=
ZENZAPIS_API_KEY=
FGMODS_API_KEY=
```

## Useful Scripts

```bash
npm start
npm run start:optimized
npm run cleanup
npm run reset-session
npm run start:fresh
```

## Warning

This is an unofficial WhatsApp automation project. It is not affiliated with WhatsApp, Meta, or any related company. Use it responsibly, do not spam, and follow all laws and platform rules. Unofficial WhatsApp bots can lead to account bans.

## Credits

- Baileys
- Original open source bot authors and contributors
- TechGod143 and Dgxeon for pair-code inspiration
