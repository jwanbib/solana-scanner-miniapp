# Solana Safe Filter Bot V3
Telegram-first Solana token scanner with paper-trading signals.

Setup:
1. Create a Telegram bot with @BotFather using /newbot.
2. Put the Bot Token in .env.
3. Put your Solana RPC URL in .env.
4. Install Python 3.10+.
5. pip install -r requirements.txt
6. python bot.py

Commands:
/start
/scan
/status
/settings
/help

Important: real trading is disabled. No private wallet key is used.
The holder concentration calculation is an approximation, not a complete
wallet-graph/security audit.
