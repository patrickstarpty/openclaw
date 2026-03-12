# CLAUDE.md

## Project Overview

This is a study repository analyzing the philosophy and architecture of **OpenClaw**, the open-source personal AI agent framework. It contains no application code -- only research documentation.

## Repository Structure

- `README.md` -- Project introduction and table of contents
- `ANALYSIS.md` -- Comprehensive architecture and philosophy analysis (600+ lines)

## Key Topics Covered in ANALYSIS.md

- **Soul System (SOUL.md)** -- Agent identity, personality, and the SOUL + USER pairing
- **Memory Architecture** -- Bootstrap memory, working memory, long-term memory (MEMORY.md, daily logs, embeddings)
- **Context Compression** -- Dream routines, pre-compaction memory flush, compaction vs. pruning
- **Skills System** -- SKILL.md directories, progressive disclosure, self-authoring, ClawHub ecosystem
- **Heartbeat** -- Cron-driven proactive behavior, HEARTBEAT_OK suppression
- **Gateway** -- Single daemon control plane, multi-channel routing, session scoping
- **Workspace Kernel** -- Bootstrap files (SOUL, USER, IDENTITY, AGENTS, TOOLS, HEARTBEAT, BOOTSTRAP, MEMORY)
- **Design Patterns** -- Flat-file state, ReAct loop, progressive disclosure, separation of identity/knowledge, self-modification
- **Comparison with Claude Code** -- Converging and diverging patterns
- **Security** -- Attack surface, architectural mitigations, fundamental tensions

## Writing Conventions

- Use `--` (double dash) for em-dashes, not unicode characters
- Use standard Markdown tables and code fences
- Keep ASCII diagrams in fenced code blocks
- Reference source materials with hyperlinks in a References section
- Section numbering follows `## N. Title` format

## Branch

- Primary development branch: `claude/openclaw-analysis-G8CBQ`
