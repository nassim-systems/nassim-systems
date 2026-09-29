# Nassim — AI systems, measured before they are built

Independent consultant, Paris. English and French. Remote across Europe.

I diagnose, design and build LLM systems for engineering and operations teams. My rule: **every component is measured before it is kept** — including the ones I end up removing.

## Proof, not claims

**[radar-automation](https://github.com/nassim-systems/radar-automation)** — a monitoring pipeline (RSS → relevance scoring → draft posts) built as a client-grade demo.

- 264 automated tests, explicit typed workflow, concurrent scoring with budget and retry
- Scoring threshold calibrated on a held-out set collected for that purpose: 100 % precision, 70 % recall — the limits are documented, not hidden
- A critic agent was built, measured, then **removed**: 67 % false rejects on 14 cases. The measurement is in the repo
- Every run traced: 17 articles, 17 LLM calls, 0 failures, 3.8 s wall-clock vs 13.4 s cumulative (×4.0), $0.008. Three runs in history, 73 calls, about $0.04 in total

Start with [`QUALITY.md`](https://github.com/nassim-systems/radar-automation/blob/master/docs/QUALITY.md), [`CRITIC_AGENT.md`](https://github.com/nassim-systems/radar-automation/blob/master/docs/CRITIC_AGENT.md) and [`OBSERVABILITY.md`](https://github.com/nassim-systems/radar-automation/blob/master/docs/OBSERVABILITY.md).

## What I offer

| | |
|---|---|
| **Diagnostic** | Fixed price, fixed scope. I read your real data (tickets, leads, documents) and tell you what is automatable, what is not, and what it costs. The document is yours even if we stop there. |
| **Architecture & build** | Scoped and priced only after the diagnostic. Typed interfaces, deterministic orchestration around the model, an evaluation set fixed before deployment. |
| **QA automation** | Playwright end-to-end tests, flaky-test repair, CI integration. |

I do not quote a build before I have seen your data.

## How I work

- Non-determinism stays at the model boundary; control flow stays deterministic.
- Evaluation comes before deployment: a fixed set, stated pass criteria.
- Findings are quantified, and I say so when the requested solution is the wrong one.
- Documentation is part of the deliverable.

## Contact

nassim.automation@gmail.com · [Upwork](https://www.upwork.com/freelancers/~01dc0627acb8089749)
