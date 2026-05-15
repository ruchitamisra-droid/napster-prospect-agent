# Napster · Prospect Research Agent

An AI-powered sales intelligence tool that generates tailored B2B partnership briefs for telco and media prospects — built for the Napster Partnerships team.

![Status](https://img.shields.io/badge/status-live-brightgreen) ![Built with](https://img.shields.io/badge/built%20with-Claude%20AI-blueviolet)

## What it does

Enter any telco or media company name and the agent instantly generates:

- **Why now** — why this company is primed for an AI media partnership
- **Pain points** — their key business challenges
- **Napster fit** — which products map best to their situation
- **Opening hook** — a punchy line for cold outreach
- **Objection handling** — the two most likely pushbacks and how to counter them
- **Deal structure** — recommended partnership model (JV, rev share, white-label, etc.)

## Tech stack

- Vanilla HTML/CSS/JS — zero dependencies, zero build step
- [Anthropic Claude API](https://anthropic.com) — `claude-sonnet-4-20250514`
- GitHub Pages for hosting

## Live demo

👉 `https://YOUR-USERNAME.github.io/napster-prospect-agent`

## Setup (5 minutes)

### 1. Fork or clone this repo

```bash
git clone https://github.com/YOUR-USERNAME/napster-prospect-agent.git
cd napster-prospect-agent
```

### 2. Enable GitHub Pages

1. Go to your repo on GitHub
2. Click **Settings** → **Pages**
3. Under *Source*, select **Deploy from a branch**
4. Select `main` branch → `/ (root)` → click **Save**
5. Wait ~60 seconds, then visit `https://YOUR-USERNAME.github.io/napster-prospect-agent`

### 3. Get an Anthropic API key

1. Sign up at [console.anthropic.com](https://console.anthropic.com)
2. Go to **API Keys** → create a new key
3. Paste it into the app when prompted (it stays in your browser, never sent anywhere else)

That's it. No server, no database, no deployment pipeline.

## Usage

1. Open the live URL
2. Paste your Anthropic API key into the field at the top
3. Type a company name (or click a quick-fill button)
4. Hit **Generate brief** — brief appears in ~5 seconds
5. Use **Copy brief** to paste into an email, Notion, or CRM

## Security note

Your API key is entered client-side and sent directly to Anthropic's API. It is never stored, logged, or transmitted anywhere else. For a team deployment, consider wrapping the API call in a lightweight backend (Cloudflare Worker, Vercel function) to keep the key server-side.

## Built by

VP Partnerships @ Napster — built to accelerate enterprise telco deal sourcing using AI agents.

---

*Not for external distribution.*
