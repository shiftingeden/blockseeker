# BlockSeeker — home miner monitor for iPhone

Monitor and control **all your home miners** over local Wi-Fi — Bitaxe, NerdQAxe, Avalon
Nano, Antminer (stock, Vnish, Braiins OS, LuxOS), Goldshell and NMAxe — with no account and
no cloud.

**Coming soon to the App Store.** Questions or early access: **TechBitsMix@gmail.com**

## Supported miners

| Hardware | Connection |
|---|---|
| Bitaxe / NerdAxe / NerdQAxe / NMAxe | AxeOS HTTP API |
| Avalon Nano 3 / 3S | cgminer API (port 4028) |
| Antminer — stock, Vnish, Braiins OS, LuxOS | cgminer/bmminer API (port 4028) |
| Goldshell (e.g. Mini-DOGE) | Goldshell HTTP API |

Algorithms: SHA-256, Scrypt (L-series, Goldshell), Equihash (Z-series).

## Features

- Auto-discovery on your network, or add by IP
- Dashboard grouped by miner type, live hashrate/temperature/power charts
- Alerts per type and per miner, with alert history
- Auto-recovery: reboot stuck or overheated miners, scheduled reboots
- Solo block odds per algorithm, earnings and electricity cost per day
- Live Activity and Home Screen widget

## Privacy

BlockSeeker only talks to miners on your own network. No analytics, no servers.
[Privacy policy](privacy-policy.html)

---

Made by [TechBitsMix](https://github.com/shiftingeden), an indie iOS developer and home miner.
Also: **[Pool Monitor](https://apps.apple.com/app/id6785621114)** (pool stats & offline alerts) ·
**[AxeSentry](https://apps.apple.com/us/app/axesentry/id6781810919)** (Bitaxe swarm monitor).
