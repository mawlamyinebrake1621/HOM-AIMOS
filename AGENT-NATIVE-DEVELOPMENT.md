# Agent-Native Development Workflow

HOM-AIMOS is architected and technically governed by **Walid Saidi** using a supervised, agent-native engineering workflow.

The project uses coding and research agents as implementation, review, testing, and verification instruments. They do **not** own the architecture, threat model, security invariants, acceptance criteria, or release claims.

## Current agent tooling

The active engineering workflow has used both:

- **OpenAI Codex** — repository-scale implementation, refactoring, code review, test construction, verification, debugging, and evidence-producing engineering tasks.
- **Nous Research Hermes Agent** — agent-assisted engineering and research workflows, including interactive repository work and implementation/review support.

Both tools have been used during current HOM-AIMOS development work as of September 2026.

## Authority model

Agent output is treated as proposed implementation or evidence, not as architectural authority.

Walid Saidi retains responsibility for:

- system architecture;
- threat models and security boundaries;
- protocol and trust-model design;
- persistent-memory semantics;
- cryptographic and authorization invariants;
- acceptance and release gates;
- interpretation of evaluation results; and
- final technical claims.

Changes produced or proposed through agent-assisted development are expected to pass the same source, security, architecture, integration, reproducibility, and live-system evidence gates as manually authored changes.

This distinction is deliberate: HOM-AIMOS is itself concerned with long-lived agent state, authority, provenance, tool use, execution history, and verifiable control. The development process therefore treats capable coding agents as systems whose context, permissions, actions, failures, and outputs require supervision and explicit verification.

## Why this is documented

HOM-AIMOS is not presented as a project whose architecture was delegated to an AI system. It is a human-owned research and engineering project built with extensive use of modern coding agents.

Documenting that workflow is relevant to the research itself: practical use of coding agents exposes many of the same questions HOM-AIMOS studies at runtime—authority separation, persistent context, tool permissions, provenance, trace integrity, failure recovery, and the difference between an agent performing work and an agent having authority to define what is correct.
