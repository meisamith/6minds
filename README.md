# 6Minds 🧠
> 6 expert minds. Real market analysis. No sugarcoating.

**Live:** https://6minds-production.up.railway.app

---

## What is 6Minds?

You pitch your startup idea. 6 world-class expert personas tear it apart — with real market data, real competitor names, real funding numbers.

Not a feel-good validator. Not a generic AI response.
A brutal, honest, market-aware analysis engine that tells you the truth before the market does.

---

## The 6 Expert Minds

| Expert | Persona | What they look for |
|--------|---------|-------------------|
| 🦈 The Shark | Cold-blooded VC | TAM, unit economics, exit potential |
| 🔥 Been There, Failed That | Failed founder | Real execution risks, why ideas die |
| 🌍 The Market Oracle | Market analyst | Real competitors, market size, timing |
| 😤 Your Target Customer | The actual user | Willingness to pay, switching costs |
| ⚔️ Your Biggest Competitor | Competitor CEO | Exactly how they would crush you |
| 💡 The Billionaire Builder | Serial founder | The one thing that makes or breaks it |

---

## Features

- **6 Expert Analysis Cards** — each with a KEY INSIGHT always visible, full analysis expandable
- **Startup Viability Score** — scored across 4 dimensions out of 100
- **Sub-scores** — Market Opportunity / Differentiation / Execution Feasibility / Timing & Trends
- **Startup Battle Plan** — after the roast, get a full rescue plan to actually succeed
- **Validate in 30 Days** — 5 specific steps to test your idea this month
- **Don't Do This** — 3 mistakes that will kill your startup
- **First Revenue** — exactly how to make your first money

---

## Scoring Guide

| Score | Verdict |
|-------|---------|
| 0–20 | Don't quit your day job |
| 21–35 | Needs serious rethinking |
| 36–50 | Interesting but needs major differentiation |
| 51–65 | Has potential — execution is everything |
| 66–80 | Strong idea. Move fast. |
| 81+ | Why are you still reading this? Go build it. |

---

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Backend | Python, Flask |
| AI | Anthropic Claude API (Haiku) |
| Concurrent Analysis | ThreadPoolExecutor (6 simultaneous calls) |
| Frontend | Vanilla JS, Pure CSS |
| Deployment | Railway |
| Database | None — stateless |

---

## Local Setup

```bash
git clone https://github.com/meisamith/6minds.git
cd 6minds
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
cp .env.example .env
# Add your ANTHROPIC_API_KEY to .env
python app.py
```

---

## Environment Variables

| Variable | Description |
|----------|-------------|
| `ANTHROPIC_API_KEY` | Your Anthropic API key |
| `FLASK_SECRET_KEY` | Any random secret string |

---

## My Other Projects

| Project | Description | Live |
|---------|-------------|------|
| **CarTruth** | Honest car ownership guide for Indian buyers | [web-production-dfc9.up.railway.app](https://web-production-dfc9.up.railway.app) |
| **AI Code Reviewer** | CLI tool that reviews your code using Claude API | GitHub |

---

## Built by

**Amith Choudhary**
[GitHub](https://github.com/meisamith)

---

*Built with Claude API — because brutal honesty is a feature, not a bug.*
