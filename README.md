# OPX Network

Privacy-first cryptocurrency ecosystem: a Monero-fork chain, non-custodial wallets,
and Telegram-native products with OPX as the settlement asset.

## Products

### OPX Chain
- Mainnet daemon (`opxd`) — Monero fork, fixed 21,000,000 OPX emission, block time tuned for solo-mining
- Wallet RPC (`opx-wallet-rpc`) — Monero-compatible JSON-RPC
- OPX base58 addresses with 8-byte / 11-char block encoding

### OPX Wallet (Android)
- **Current: v0.1.11 — non-custodial, built on a Cake Wallet fork** (`org.opxnetwork.wallet`).
  Seed stays on device, local `libmonero_wallet2_api_c.so` wallet engine, server only as daemon RPC.
  Latest builds and checksums: [opx-wallet-android releases](https://github.com/tgpautina-jpg/opx-wallet-android/releases).
- Legacy React-Native generations (custodial v1.1.x, v3.x) archived as older releases
  and legacy source in [opx-wallet-src](https://github.com/tgpautina-jpg/opx-wallet-src).

### Telegram ecosystem (built on OPX)
- **Finance assistant bot** — voice/photo/text expense tracking, budgets, Telegram Premium paid in OPX (aiogram 3 + SQLite)
- **CPA network bot** (in review) — subscribe-to-earn offers with OPX escrow, holds, antifraud
- **Market v2** — Telegram store accepting OPX payments
- **Radio / store / community services** — payments in OPX via wallet RPC

## Notes
- Repos under this account carry release artifacts and sanitized sources only —
  no seeds, keys, RPC credentials, or internal infra configs.
- Wallet APKs are also mirrored at opxnetwork.duckdns.org.
