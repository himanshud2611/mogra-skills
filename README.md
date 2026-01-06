# Mogra Skills

Automated skills and workflows powered by Mogra.

## 🌅 Morning Briefing

Sends your daily Cal.com schedule to Telegram at **9:00 AM IST**.

### What it does
- Fetches today's meetings from Cal.com
- Shows upcoming meetings this week
- Sends formatted summary to your Telegram

### Setup

Add these secrets to your repo (`Settings → Secrets → Actions`):

| Secret | Description |
|--------|-------------|
| `CAL_API_KEY` | Your Cal.com API key |
| `TELEGRAM_BOT_TOKEN` | Telegram bot token from @BotFather |
| `TELEGRAM_CHAT_ID` | Your Telegram chat ID |

### Manual Trigger

Go to `Actions → Morning Briefing → Run workflow` to test.

---

Built with [Mogra](https://mogra.dev)
