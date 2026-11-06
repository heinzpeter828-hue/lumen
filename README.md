# Lumen

Lumen is a Discord bot that helps you grow your community and run your mod team. It is free to start and set up in about two minutes.

**This repository contains documentation only (not the bot's source code).**

## What it does

- **Server Coach:** a weekly report with a health score, who joins and leaves, busiest times and plain-language tips on what to improve. Only counters are stored, never message content.
- **Mod Desk:** ban appeals in Discord, private mod notes, a team overview and shift handover.
- **Moderation:** warn, timeout, temp-ban, AutoMod, anti-raid, numbered cases and a mod log.
- **Tickets:** claim, priority, close requests, ratings, transcripts and team stats.
- **Applications:** `/apply`, templates (moderator, helper, event team, partnership), team votes, interview channels and history.
- **Giveaways:** requirements, bonus entries, scheduled start and re-rolls.
- **Welcome cards, levels and role rewards.**

## Add Lumen

[Add Lumen to your server](https://discord.com/oauth2/authorize?client_id=1568181508156690513&permissions=1099780189270&integration_type=0&scope=bot+applications.commands)

Then run `/quicksetup` and `/doctor`. Move Lumen's role above the roles it should manage (Server Settings → Roles).

## Permissions, and why

Lumen never asks for Administrator.

| Permission | Why |
|---|---|
| View Channels, Send Messages, Embed Links, Attach Files, Read Message History, Add Reactions | Post and read where you set it up (panels, cards, transcripts) |
| Manage Channels | Ticket and interview channels |
| Manage Roles | Autorole, accepted-application role, button roles |
| Manage Messages | AutoMod and `/mod clear` |
| Kick, Ban, Timeout Members | Your moderation commands |

Privileged intents: **Server Members** (welcome messages, autorole, level rewards) and **Message Content** (AutoMod, XP, custom commands, ticket transcripts).

## Your data

- Normal chat messages are not stored. Only counters are saved.
- `/forgetme` deletes your own data on a server.
- A server's data is removed 30 days after the bot leaves.

Full details: [Privacy Policy](https://heinzpeter828-hue.github.io/lumen/privacy.html) · [Terms of Service](https://heinzpeter828-hue.github.io/lumen/terms.html)

## Help

- Support server: [ADD YOUR NEVER-EXPIRING INVITE LINK HERE]
- Email: lumenbot.support@gmail.com
