# Luke Hanna

Senior at USC — Computer Science + Business Administration. Based in Los Angeles.

Fascinated by what AI makes possible. I build end-to-end to learn — product shape, systems, data pipelines, UI, deployment, the whole thing. The projects below are all self-initiated.

## What I'm building

- **[PFC — Personal Finance Coach](https://github.com/llukehanna/PFC-docs)** — single-user system that holds the full state of my finances and checks every action against the credit-card plan's gates (5/24, utilization at close, SUB windows) before it happens. Append-only SQLite ledger, Plaid + SimpleFIN ingest, a 20-rule opportunity-cost comparator over versioned assumption ranges, tax-aware 5-year projection, MCP server so Claude is the primary interface, Next.js UI behind Cloudflare Access. TypeScript on Node 24, ~84K LOC + 3,100 tests. *Source private by design; full engineering docs at the link.*

- **[Clippers Command Center](https://github.com/llukehanna/Clippers-Command-Center)** — live NBA analytics dashboard for Clippers fans. Next.js 16 + Neon Postgres, Vercel Cron data pipeline, deterministic "provable insights" engine.
  [clippers-command-center.vercel.app](https://clippers-command-center.vercel.app)

- **[BJS — Blackjack Strategy](https://github.com/llukehanna/Blackjack-Strategy)** — native iOS app (Swift 6.2 / SwiftUI / SwiftData). Basic-strategy drills, Hi-Lo counting, house-edge calculators, full card-counting sim.

- **[BT — Kalshi Weather Edge Bot](https://github.com/llukehanna/BT-docs)** — Python research bot testing whether GFS ensemble forecasts beat Kalshi's daily temperature markets. Full pipeline from forecast to fee-adjusted edge to Kelly sizing to NWS settlement, 13K LOC + 945 tests, four months unattended, 7,440 settled signals. Result: the market price out-predicts the model and the calibration gate blocked trading, which is what it was built to do. Now running a maker-side market-making experiment on the same books. *Source private; results and engineering docs at the link.*

---

[luke@zhannas.com](mailto:lllukehanna@gmail.com) · Los Angeles
