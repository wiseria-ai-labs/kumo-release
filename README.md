# Kumo

**A lightweight, powerful workbench for your coding agents.** Run several coding agents on your Mac
at once, all in one window. Give each task its own git worktree so they don't overwrite each other's
changes, and answer them from your phone.

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://amkumo.com/hero-dark.webp">
  <img src="https://amkumo.com/hero-light.webp" alt="The Kumo workbench: two agents side by side in a split view, each in its own tab, with projects, worktrees and running agents down the left.">
</picture>

## Download

**[Download for Mac →](https://github.com/wiseria-ai-labs/kumo-release/releases/latest/download/Kumo.dmg)**

Apple Silicon, macOS 13 or later. Open the DMG and drag Kumo to Applications — it is signed and
notarised, so it opens on the first double-click.

You also need at least one agent CLI installed and signed in. Kumo ships none.

## What it does

**Side by side.** Drag a tab to one side and the view splits, up to four conversations. Each keeps its
own scroll position, draft and model, and the input box at the bottom goes to whichever one you
clicked last. To keep agents out of each other's way, start each task on a new branch: Kumo creates
a git worktree for it, so the agents on it work in their own folder.

**Agentflows.** Nodes are agents with prompts, edges are conditions, and every step commits a
checkpoint you can rerun from. Start one by hand, on a schedule, or from an event — a GitHub issue
opening is an event, so a flow can pick up work before you have read it. Approval nodes wait for a
human.

**Remote Control.** Scan a code once and read, reply, approve or stop from your phone. Your Mac
dials out to a relay and never listens on a port, so there is nothing to configure. The relay
carries ciphertext it cannot read — the key is in the fragment of the pairing URL, which a browser
never sends to a server.

## Works with

Claude · Cline · Codex · Copilot · Cursor · DeepSeek Harness · Gemini · Goose · Grok · Hermes ·
Kilo Code · Kimi Code · OpenCode · Pi · Qwen Code

Install and sign in to the CLI and Kumo can drive it. No agent is the default, none is bundled, and
your models, MCP servers, hooks and rules stay in each CLI's own configuration.
[Install commands for all of them →](https://amkumo.com/docs/set-up-an-agent/)

## Free while in beta

**No account needed. Until 1 November 2026.** Everything is unlocked, Remote Control included.
After that, [pricing](https://account.amkumo.com/pricing) is $10/month or $100/year, with a free
tier that keeps working.

## Feedback

Bugs go in [Issues](https://github.com/wiseria-ai-labs/kumo-release/issues) here. There is a
bounty during the beta:

> Every issue we label `confirmed` earns you one month of Kumo Personal, up to 12 months per
> account, granted when the beta ends. Feature requests are welcome but don't count.

The app has a **Report a bug** button in Settings that opens the form with your version already
filled in.

## Docs

[amkumo.com/docs](https://amkumo.com/docs/) — install, set up an agent, projects and worktrees,
chat, board and split, tasks and agentflows, working with several agents, Remote Control,
troubleshooting.

[Changelog](https://amkumo.com/changelog/) · [Privacy](https://amkumo.com/privacy/) ·
[Terms](https://amkumo.com/terms/)

## About this repository

**This repo holds releases and issues.** Kumo is not open source and the source is not here.

**Privacy:** the app has zero telemetry. It contacts a server only to sign in, renew a
subscription, or reach the Remote Control relay. Your code and conversations never leave your Mac
through us. [Full policy →](https://amkumo.com/privacy/)
