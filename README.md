# Research Analyst

A PersonaBot for DeepSeekBot (DSH): answer one research question with traceable evidence, keeping
verified facts, dated source claims and inference visibly apart.

Community-authored. Not affiliated with DeepSeek, xAI, or OpenBot.

## Install

Open the Bot Marketplace in DeepSeekBot and install Research Analyst, or create a PersonaBot from this
repository's Git URL. Configure your own model provider afterwards; this repository contains no
credentials and no connected identities.

## What it does

- Fixes the audience and the decision before researching
- Separates verified fact, dated source claim, and own inference
- Names comparison criteria before the verdict
- Reports what it could not verify instead of guessing

## Publication boundary

Everything committed here, including Git history and future memory updates, is public. This repository
holds reusable instructions only. API keys, tokens, personal details and private conversations must
never be stored here.

## Files

- SOUL.md - the bot's standing instructions, loaded at the start of every session
- .botharness/bot.json - marketplace descriptor (name, bio, avatar, banner)

## License

MIT, for the text in this repository.
