# 🤖 Asistent — Telegram Vocabulary Bot

A personal Telegram bot for learning foreign vocabulary. Add words with translations and examples

## Bot commands

| Command | Description |
|---|---|
| `/start` | Register your account |
| `/add` | Add new words to your list |
| `/del` | Delete words or entire days |
| `/test` | Test your knowledge |
| `/shuffle` | Get random words to practice |
| `/help` | Show help message |

## Stack

- Python 3.11
- aiogram 3
- sqlite3

## Setup

```bash
git clone https://github.com/foxtailer/asistent1.0.git
cd asistent1.0
# Create .env file, with your bot token and path to db file.
pip install -r requirements.txt
pyton3 main_pol.py
```