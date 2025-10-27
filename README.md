# Solence AI

**AI-powered security infrastructure for Solana**

We're building tools that make it easier to trust wallet addresses on Solana. Our first product is a security scanner API that gives you instant risk assessments on any wallet.

## What we're shipping

**[solenceai-api](https://github.com/solenceai/solenceai-api)** - REST API for wallet security analysis  
Get deterministic risk scores, AI insights, and mint on-chain safety badges for qualifying wallets. Built with TypeScript, powered by OpenAI, runs on Solana mainnet.

```bash
curl -X POST https://solenceai.com/api/scan \
  -H "Content-Type: application/json" \
  -d '{"wallet": "YOUR_WALLET_ADDRESS"}'
```

**Why this matters:**  
DAOs need to vet multisig signers. DeFi protocols want to screen high-value users. OTC traders need counterparty due diligence. We handle the security analysis so you can focus on building.

## Quick stats

- 🎯 Deterministic scoring
- ⚡ Sub-second response times
- 🔓 10 free scans/hour, no auth required
- 🛡️ SPL token badges for verified wallets

## Core tech

- Solana Web3.js for blockchain data
- OpenAI for natural language insights
- MongoDB for scan history
- TypeScript throughout

## Links

- Live API: [solenceai.com](https://solenceai.com)
- Playground: [solenceai.com/playground](https://solenceai.com/playground)
- Docs: [solenceai.com/docs](https://docs.solenceai.com/docs)
- Twitter: [@SolenceAi]([https://twitter.com/SolenceAi](https://twitter.com/SolenceAi))

## Get in touch

Building something that needs wallet security checks? Have ideas for what we should build next?

- **Email:** support@solenceai.com
- **Twitter:** [Join community]([https://twitter.com/SolenceAi](https://twitter.com/SolenceAi))
- **Issues:** Open them in [solenceai-api](https://github.com/solenceai/solenceai-api/issues)

---

MIT licensed. Built for the Solana ecosystem.
