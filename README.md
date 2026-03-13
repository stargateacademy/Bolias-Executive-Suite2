# Bolias Bank — AI Executive Suite

Management demo for Bolias Bank SRHFI. Five AI executives governing an AED-backed stablecoin in real time.

## Quick Start

```bash
npm install
npm run dev
```

Open [http://localhost:3000](http://localhost:3000)

## Deploy to Vercel

1. Push this repo to GitHub
2. Go to [vercel.com](https://vercel.com) → New Project → Import your repo
3. Leave all defaults → Deploy
4. Live in ~60 seconds

## What's inside

- **Command Centre** — live metrics dashboard, all 5 AI agents, 6 customer journey launchers
- **Agent Chat** — direct chat with CEO / CFO / CRO / COO / CCO. Quick prompts return instant sample responses. Custom questions call Claude API live.
- **Customer Journeys** — all 6 journeys animate step-by-step and auto-trigger the relevant agent

## Stack

- React 18 + Vite
- Anthropic Claude API (claude-sonnet-4-20250514)
- No backend required — pure frontend

## Notes

- Quick-prompt buttons use pre-written sample responses (no API key needed for demo)
- Custom typed questions call the Anthropic API directly from the browser
- All data is testnet / simulated — no real AED transactions
