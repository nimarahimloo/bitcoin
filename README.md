# ZarCoin (ZAR)

**A new independent cryptocurrency forked from Bitcoin Core.**

- **Name:** ZarCoin
- **Ticker:** ZAR
- **Repository:** https://github.com/nimarahimloo/bitcoin
- **Working branch:** `new-currency`

## Goal
Create a real, working, independent blockchain currency based on Bitcoin Core technology.

## Current Status (2026-10-17)

✅ Forked Bitcoin Core  
✅ Created dedicated branch `new-currency`  
✅ Project renamed to ZarCoin  
🔄 Network parameters being customized (message start, ports, address prefixes, seeds)  
⏳ New genesis block (required for a completely clean independent chain)  
⏳ Build & test  
⏳ First nodes & mining

## How to make it really work

1. Change network magic bytes, port, address prefixes and HRP so it never connects to Bitcoin.
2. Generate a **new genesis block** (new timestamp + nonce that satisfies the difficulty).
3. Clear all Bitcoin seeds and checkpoints.
4. Compile the node.
5. Run at least 2 nodes and start mining.

The code is ready for these changes. The hardest remaining technical step is mining a valid new genesis block (can be done with a small C++ program or by temporarily lowering difficulty).

## License
MIT (same as Bitcoin Core)

---
Original Bitcoin Core content follows for reference.

Bitcoin Core integration/staging tree
=====================================

https://bitcoincore.org
