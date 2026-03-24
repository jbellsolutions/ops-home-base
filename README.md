# Ops Home Base

**Your AI-Powered Operations Command Center**

An open-source template for operations managers who want a single command center to manage their entire workflow. Built to work with Claude Code and MCP (Model Context Protocol) integrations, it connects ClickUp, Go High Level CRM, Gmail, and Google Calendar into one unified dashboard. No coding required.

![Dashboard Preview](./preview.png)

---

## What It Does

- **Unified view** of calendar, email, tasks, and CRM pipeline — all in one place
- **Natural language commands** via Claude Code ("Create a task for Sarah...", "What's on my calendar today?")
- **Real-time data** from all connected platforms via MCP
- **Zero coding required** — built for operations managers, not developers
- **Works locally on your computer** — your data stays private

---

## Supported Integrations

| Integration | Status | Connection |
|---|---|---|
| ClickUp | Ready | MCP |
| Go High Level CRM | Ready | MCP / API |
| Gmail | Ready | MCP |
| Google Calendar | Ready | MCP |
| Slack | Ready | MCP |
| HubSpot | Coming Soon | MCP |
| Notion | Ready | MCP |
| Google Drive | Ready | MCP |

---

## Quick Start

```bash
# 1. Clone the repo
git clone https://github.com/UsingAIToScale/ops-home-base.git
cd ops-home-base

# 2. Open the dashboard
open index.html    # macOS
# or just double-click index.html in your file manager

# 3. Connect your tools via Claude Code
# Install Claude Code, then connect your MCP integrations
# See the Setup Guide below for details
```

---

## Setup Guide

### 1. Install Claude Code

Download and install Claude Code from [claude.ai/code](https://claude.ai/code). This is the AI assistant that powers the natural language interface for your dashboard.

### 2. Connect ClickUp MCP

1. Open Claude Code and navigate to **Settings > MCP Integrations**
2. Search for **ClickUp** and click **Connect**
3. Authorize Claude Code to access your ClickUp workspace
4. Select the spaces and lists you want to manage from the dashboard

### 3. Connect Gmail MCP

1. In Claude Code, go to **Settings > MCP Integrations**
2. Search for **Gmail** and click **Connect**
3. Sign in with your Google account and grant access
4. Your inbox, drafts, and sent mail will now be accessible via natural language commands

### 4. Connect Google Calendar MCP

1. In Claude Code, go to **Settings > MCP Integrations**
2. Search for **Google Calendar** and click **Connect**
3. Authorize access to your calendars
4. You can now create, view, and manage events through Claude Code

### 5. Connect Go High Level CRM

1. Log into your Go High Level account
2. Navigate to **Settings > API Keys** and generate a new API key
3. In Claude Code, go to **Settings > MCP Integrations**
4. Search for **Go High Level** and click **Connect**
5. Paste your API key when prompted
6. Your CRM pipeline, contacts, and opportunities will be available through the dashboard

---

## How to Use

The dashboard is your visual reference — a single screen that shows what matters across all your tools. But the real power comes from talking to Claude Code. Instead of switching between five different apps, you just tell Claude what you need in plain English.

Here are some example commands to get you started:

- **"What's on my calendar today?"** — Get a quick summary of your schedule without opening Google Calendar
- **"Create a ClickUp task for the team to review the Q1 report by Friday"** — Instantly create and assign tasks with deadlines
- **"Check my unread emails and summarize the important ones"** — Triage your inbox in seconds instead of scrolling through dozens of messages
- **"Move the Johnson deal to the proposal stage in CRM"** — Update your pipeline without logging into Go High Level
- **"Draft a follow-up email to the client about the project timeline"** — Generate professional emails ready for your review
- **"Give me a weekly operations summary"** — Get a cross-platform report covering tasks completed, emails sent, meetings held, and deals progressed

The more you use it, the more natural it feels. Think of Claude Code as your operations co-pilot — you give the instructions, it handles the execution across all your tools.

---

## Built With

- **HTML / CSS** — Single file, no frameworks, no build step
- **Claude Code** — AI assistant that powers the natural language interface
- **MCP (Model Context Protocol)** — The integration layer that connects your tools to Claude Code

---

## About

Built by [UsingAIToScale.com](https://usingaitoscale.com) — helping businesses leverage AI to streamline operations without needing a development team.

---

## License

This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.

## Sales & Marketing Materials

The `sales/` directory contains the complete sales offer for this product including:
- Full sales page copy (Todd Brown direct response style)
- 5-email nurture sequence
- Social media content (LinkedIn, Twitter, YouTube, Instagram)
- Landing page copy
- Cold outreach templates
- Product ladder and pricing
- Funnel architecture

See also: [AI Integrators Sales Launch Kit](https://github.com/jbellsolutions/ai-integrators-sales-launch-kit) for all 5 offers in one place.
