# CIS Harness

**Purpose:** A reusable, project-agnostic harness that provides guardrails, rituals, and policies to prevent LLM workflow collapse.

**Scope:** Policy docs, templates, and (later) optional CI jobs/scripts. **No project content** lives here.

**Principles**
- Minimal Viable Enforcement first; add layers only when stress signals justify them.
- Offline/cheap by default; budget-capped telemetry; brownout/kill-switch ready.
- Reversible adaptations with sunset timers and decision logs (in the consuming repo).

**Consume this repo**
- As a git submodule in CIS at `/harness`, or
- Copy-select files into CIS when you only need a subset.

Next step: add OPS/OBS policies and lightweight gates in small, stress-signaled PRs.
