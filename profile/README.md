# Skill++

![Skill++ banner](https://raw.githubusercontent.com/skillpp/skillpp/main/assets/skillpp-banner.png)

**Skill++ coordinates specialized AI skills into structured workflows for on-chain intelligence.**

Skill++ is a protocol-first AI skill package for routing, sequencing, cross-checking, and guarding multi-agent Web3 workflows. It helps AI agents coordinate token research, wallet review, smart-contract audit, smart-money tracking, chain scanning, and write-operation handoff without treating every skill as an isolated tool.

## Start

```bash
npm install -g skillpp
skillpp doctor
skillpp skills
```

Use the protocol with an AI agent:

```text
Use Skill++ from this repository. Read SKILL.md first, then skillpp.manifest.json and the matching adapter under adapters/ for your runtime.
```

## Project

| Link | Destination |
|---|---|
| Main repository | https://github.com/skillpp/skillpp |
| npm package | https://www.npmjs.com/package/skillpp |
| Website | https://skillpp.ai |
| X | https://x.com/SkillppAI |

## What Skill++ Provides

| Layer | Purpose |
|---|---|
| Router | Parses URLs, addresses, symbols, source snippets, wallets, and natural-language intents |
| Pipeline Protocol | Maps requests to stable pipeline IDs |
| Skill Registry | Registers coordinated skills across Binance Web3, Binance Exchange, Four.meme, audit-plus, and Skill++ modules |
| Handoff | Emits structured JSON so downstream skills can continue without losing context |
| Risk Fusion | Cross-checks audit, market, smart-money, wallet, and social signals |
| Safety | Blocks sensitive actions behind checkpoints and explicit user confirmation |
| Agent Adapters | Provides loading guidance for BinanceAI, Claude, GPT, Gemini, Kimi, Mimo, OpenClaw, and Codex |

## Safety Boundary

Skill++ is not a wallet, exchange, or Four.meme SDK. Read-only analysis can run locally where supported; write-operation flows are checkpointed handoffs unless the user installs and explicitly invokes the matching external CLI.

Skill++ output is for research and risk review only. It is not financial advice.
