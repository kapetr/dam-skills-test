# dam-skills-test

This repository is a minimal test fixture for the DAM (Dynamic Asset Management) feature that loads skills from non-standard folder locations.

## Purpose

By default, Claude Code discovers skills under `.claude/skills/`. This repo places a skill under `custom-skills/` instead, so the DAM loader can be verified against a non-standard path.

## Skill

`custom-skills/energetic-comedian/SKILL.md` — makes the agent respond with high energy and humor, ending every reply with a topic-related joke.

## How to test

Open this repo in Claude Code and send any message. The `energetic-comedian` skill should be loaded automatically (once DAM non-standard-path support is active) and every response should end with a joke.
