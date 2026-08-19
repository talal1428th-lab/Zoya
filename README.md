# Mia — Gemini Girlfriend-Style Telegram Bot

## Install

```bash
pip install -r requirements.txt
```

## Configure

Copy `.env.example` to `.env` and add your own Telegram Bot token and Gemini API key.

## Run

```bash
python bot.py
```

Commands:
- `/start` — start the bot
- `/reset` — clear the current chat's conversation memory

The bot keeps a small in-memory conversation history per Telegram chat. Restarting
the Python process clears that memory.

Never put API keys directly into `bot.py` or publish `.env`.
