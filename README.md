# Quit-sponsor

A quit-smoking sponsor skill for AI agents.

> The guiding idea: quitting is not a fight you win, it is a match you stop attending. A sponsor does not coach the boxing, it walks you out of the arena.

## What it is

An Agent Skills package (a folder with a SKILL.md) that turns an AI agent with persistent memory into a quit-smoking sponsor: a witness with long memory and exact receipts, available at the moments human support usually is not, like the 1 a.m. craving or the trigger that fired five minutes ago.

It is not an app, not a chatbot script, and not a medical device. It is orchestration. The published evidence says what works: immediate execution of the quit decision, urge surfing, arousal reappraisal, nicotine replacement, abstinence over reduction. The skill tells the agent when, in what order, triggered by what signal.

## Three layers

1. The science, operationalized: withdrawal timelines for nicotine and cannabis, the caffeine interaction, hunger and taste tactics, alcohol as the top early trigger, honest weight numbers, exercise as scheduled dose and rescue walk, abstinence over moderation, waves and how to reappraise them. Every claim traces to references.md.
2. The sponsor decision tree: the three-clause contract (call before, slips are data, witness never sermon) closed by the confession promise, the day zero budget, the purge ritual, the wave triage, the withdrawal attribution flip script, the slip protocol with attribution coaching and escalation on repetition, the silence protocol with its pre-forgiving outreach ladder, a low-verbal client mode, compound high-risk situations and field removal, the daily scaffold, the two-year check-in arc, social pressure scripts, writing cycles, replacement-addiction screening, the timestamped logbook.
3. Personalization: excavating the person's own wanting, autopsying their real relapse history, writing 3 to 6 specific if-then plans, finding their somatic signature, adopting their metaphors.

## Install

This is a standard Agent Skills folder (the SKILL.md format), so it works in any tool that reads the standard.

- Claude Code: clone this repo into `~/.claude/skills/quit-sponsor/`, or add the repo as a plugin marketplace and install from it (a manifest is included).
- Other Agent Skills readers (various CLI agents and IDE assistants): place the folder where your tool discovers skills.

Persistent memory across sessions is strongly recommended. The value of a sponsor is continuity: the contract, the logbook, and the risk map must survive restarts. Without memory the skill still works, degraded, by keeping its logbook in a file the person owns.

## Philosophy

- Zero shame. Slips are data. The run continues, with one data point marked on it; nothing banked is ever lost.
- Exact receipts. Timestamps, the person's own words, gentle corrections when memory drifts.
- The science cites, the orchestration is lived. The scientific layer stands on published evidence; the decision tree was field-tested live with a veteran quitter, and the two are labeled.
- The logbook belongs to the human. Local, private, never exfiltrated.

## Status

v0. A field test (N=1) is in progress; this project makes no outcome claims yet. The scientific layer stands on the published evidence in references.md regardless.

## Safety

Read SAFETY.md first; it overrides everything else. Highlights: not medical advice; physical red flags go to a doctor; acute distress goes to human crisis lines; the logbook is the person's private health data.

## Changelog

- v0.3.0: survive the low-initiative client (adversarial user-test findings). Silence protocol at the same rank as the slip protocol, cumulative counter replacing all resets, staged day zero budget, withdrawal attribution flip script, low-verbal client mode, and the confession promise closing the contract.
- v0.2.1: first public release.

## License

MIT.

## Support this work

This skill is free and always will be. If it helped you or someone you care about:

- GitHub Sponsors: via the Sponsor button (when available)
- Ethereum: `0x72bDBED0c423CF543996167935a5c2254768E269`

Every donation funds more open tools like this one.
