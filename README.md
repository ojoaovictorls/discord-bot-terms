# Discord Minecraft Bedrock Server Control Bot

This project is a private Discord bot designed to control a Minecraft Bedrock Dedicated Server remotely through Discord commands.

## Features
- Start and stop the Minecraft Bedrock server
- Start and stop the playit.gg tunnel
- Display server online/offline status
- Simple command-based control
- Designed for private use

## Requirements
- Windows 10 or later
- Node.js v18 or higher
- Minecraft Bedrock Dedicated Server
- playit.gg client
- Discord Bot Token

## Installation

1. Install dependencies:
```bash
npm install discord.js dotenv

    Create a .env file in the project root:

DISCORD_TOKEN=YOUR_DISCORD_BOT_TOKEN

    Configure paths in index.js:

const BEDROCK_DIR = "C:/ServidorBedrock";
const BEDROCK_EXE = "bedrock_server.exe";
const PLAYIT_EXE = "playit.exe";

Discord Commands
Command	Description
!server on	Starts the Bedrock server and playit
!server off	Stops the Bedrock server and playit
!status	Shows the server status
Running the Bot

Start the bot using:

node index.js

The bot will remain online while the terminal is open.
Security Notes

    This bot is intended for private use only

    Do not share your bot token

    Restrict command usage to trusted users

    Avoid using administrator permissions

Disclaimer

This software is provided "as is".
The author is not responsible for server downtime, data loss, or misuse.
License

This project is for personal and educational use only.
