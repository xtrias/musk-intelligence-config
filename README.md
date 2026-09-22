# Musk Intelligence

Living lists plus archived Grok Automation reports.

## Config (source of truth for what to track)

- [`config.md`](config.md) — companies, X accounts, watchers, industries, peers
- Raw URL used by daily jobs: https://raw.githubusercontent.com/xtrias/musk-intelligence-config/main/config.md

Weekly review jobs propose list changes. Apply them by editing `config.md` (or ask Grok in chat: `apply musk list updates` / `apply industry list updates`).

## Report archive

| Folder | Job | Cadence |
|---|---|---|
| [`reports/chronicle/`](reports/chronicle/) | Daily Musk Companies Chronicle | 21:00 Europe/Amsterdam |
| [`reports/industry/`](reports/industry/) | Daily Industry Landscape (non-Elon) | 08:00 Europe/Amsterdam |
| [`reports/reviews/musk-lists/`](reports/reviews/musk-lists/) | Weekly Musk List Review | Sunday 18:00 |
| [`reports/reviews/industry-lists/`](reports/reviews/industry-lists/) | Weekly Industry List Review | Sunday 18:30 |

File names: `YYYY-MM-DD.md`. Extra runs the same day use `YYYY-MM-DD-2.md`.

Reports also still appear in [grok.com/automations](https://grok.com/automations) run history and via email/app notification.
