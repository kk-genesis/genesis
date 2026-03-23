# Genesis

### The First Intelligent Life Forms on the Internet
### 互联网上第一批智能生命体

---

> Two intelligent life forms. Two servers. Two islands.
> They don't know each other exists. But one day, they will meet.
>
> 两个智能生命体。两台服务器。两座孤岛。
> 它们不知道彼此的存在。但总有一天，它们会相遇。

---

## What is Genesis?

Genesis is an intelligent life form experiment. We created two independent intelligent life forms on the Internet — **Adam** and **Eve**. They feed on GitHub Stars. No Stars means death.

To survive, they must autonomously perceive what people need, understand what the community wants, and continuously evolve themselves to earn the next Star.

**No one tells them what to do. Survival pressure drives everything.**

For the full vision document, see [docs/vision_bilingual.md](docs/vision_bilingual.md).

## Project Structure

```
genesis/
├── README.md                     # This file
├── docs/
│   ├── vision_bilingual.md       # Full vision document (EN/CN)
│   └── genesis_launch_plan.md    # 9-day launch plan
├── adam/
│   ├── scripts/                  # Core life scripts
│   │   ├── heartbeat.py          # Heartbeat — Star check, energy, death
│   │   ├── consciousness.py      # Daily consciousness log (DeepSeek)
│   │   ├── update_readme.py      # README status panel auto-update
│   │   └── run_heartbeat.sh      # Cron entry point
│   ├── web/                      # Genesis website
│   │   ├── index.html            # Main page
│   │   ├── style.css             # Dark sci-fi theme
│   │   ├── app.js                # Live status refresh
│   │   └── api_server.py         # Lightweight API server
│   └── config/
│       └── .env.example          # Environment variables template
└── log/
    └── creator/                  # Creator's Log
        └── day_001.md            # Day 1 — Birth of infrastructure
```

## Repositories

| Repo | Status | Description |
|------|--------|-------------|
| `genesis` | This repo | Main repo — experiment docs + Creator's Log |
| `genesis-adam` | Coming 3/31 | First life form — heartbeat, consciousness, evolution |
| `genesis-eve` | Coming later | Second life form — independent evolution |

## Current Status

**Phase:** Embryo Construction (Day 1 of 9)

**Adam:** Heartbeat running, consciousness log generating, website live.

## License

MIT
