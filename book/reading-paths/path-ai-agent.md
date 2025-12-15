---
id: urn:swd:toc:v2:readingpath:ai-agent
title: "Reading Path — AI Agent"
type: ReadingPath
audience: ai-agent
status: draft
focus:
  - semantics
  - constraints
  - safety
  - explainability
---

# Reading Path — AI Agent

This path defines **what an agent must understand before acting**.

It is also how humans should evaluate agent readiness.

## Core ontology

- → [Semantics 01 — Entities as Interaction Primitives](urn:swd:toc:v2:semantics:01)
- → [Semantics 03 — States and Transitions](urn:swd:toc:v2:semantics:03)
- → [Semantics 07 — Capabilities as Actions](urn:swd:toc:v2:semantics:07)

## Constraints and safety

- → [Semantics 08 — Side Effects](urn:swd:toc:v2:semantics:08)
- → [Ops 03 — Guardrails](urn:swd:toc:v2:ops:03)

## Accountability

- → [Dual 03 — Intent Capture](urn:swd:toc:v2:dual:03)
- → [Dual 05 — Explainability UI](urn:swd:toc:v2:dual:05)
- → [Dual 06 — Audit Surfaces](urn:swd:toc:v2:dual:06)

## Halting conditions

- → [Dual 08 — Safe Stops](urn:swd:toc:v2:dual:08)

## Terminal condition

If any of the above is missing, the agent must not act.
