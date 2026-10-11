# 🐋 Kalshi Whale Tracker

**Live site → [glibey.github.io/kalshi-whales](https://glibey.github.io/kalshi-whales/)**

A live tracker of large trades ("whales") on [Kalshi](https://kalshi.com) prediction markets: every taker order of **$10,000+** across sports, politics, crypto, economics and more, with win/loss results once markets settle.

| | |
|---|---|
| 📡 Telegram channel (free, $25k+ trades & 🔥 clusters) | [@KalshiWhaleAlerts](https://t.me/KalshiWhaleAlerts) |
| 🤖 Custom alerts bot (your own size & categories) | [@KalshiWhaleAlerts_bot](https://t.me/KalshiWhaleAlerts_bot) |

## What's on the site

- **All markets** — biggest whale trades of the last 24h, every $10k+ trade of the last 7 days, 24h whale volume.
- **Whale scorecard** — win rate of settled whale trades vs. the price they paid (the market-implied probability), and ROI. Whales only "beat the market" if they win more often than the price implied.
- **Pages per league / category** — [NFL](https://glibey.github.io/kalshi-whales/nfl/), [College Football](https://glibey.github.io/kalshi-whales/college-football/), [NBA](https://glibey.github.io/kalshi-whales/nba/), [MLB](https://glibey.github.io/kalshi-whales/mlb/), [NHL](https://glibey.github.io/kalshi-whales/nhl/), [Soccer](https://glibey.github.io/kalshi-whales/soccer/), [Tennis](https://glibey.github.io/kalshi-whales/tennis/), [UFC](https://glibey.github.io/kalshi-whales/ufc/), [Golf](https://glibey.github.io/kalshi-whales/golf/), [Politics](https://glibey.github.io/kalshi-whales/politics/), [Economics](https://glibey.github.io/kalshi-whales/economics/), [Crypto](https://glibey.github.io/kalshi-whales/crypto/), [Mentions](https://glibey.github.io/kalshi-whales/mentions/).

The site is regenerated automatically every 10 minutes.

## How trades are tracked

1. Kalshi publishes every fill on its public trade feed.
2. Fills with the same market, side and timestamp are grouped into one **taker order**; orders of $10k+ are recorded.
3. Noise is filtered out: near-settled sweeps at **97¢+** and multi-leg parlays.
4. When a market settles, each recorded order is marked **won** or **lost**.

Kalshi trades are anonymous — the tracker follows orders, not people.

## Disclaimer

Not affiliated with Kalshi or Polymarket. Data comes from public feeds and may be delayed or incomplete. Nothing here is financial advice.
