# Daniel Wahnich

<img src="daniel-portrait.jpg" align="right" width="150" alt="Daniel Wahnich">

Founder, Aweb ~ independent researcher in runtime safety for autonomous systems.

I build [Aweb](https://aweblabs.ai), mission-control infrastructure for AI agent workforces: agents do the work, a trust runtime governs it, and every action leaves a verifiable receipt. In parallel I do independent research on closed-loop safety evaluation of autonomous driving planners. Both run on the same process: pre-registered experiments, published nulls, and results that regenerate from committed evidence.

## Selected work

**[Sentinel](https://sentinel.danielwahnich.dev)** ~ runtime safety monitor for a frozen end-to-end driving planner, developed over 50 pre-registered iterations. Independently reproduces the NeuroNCAP UniAD baseline (2.12 vs the published 1.84, corroborated by DMAD's independent rerun) and lifts the monitored benchmark score to 2.91 (95% CI on the delta [+0.605, +0.928]), at a deployment cost statistically indistinguishable from zero. Stated with equal weight: the same frozen monitor, unretuned, buys no measurable benefit on a second closed-loop benchmark (HUGSIM), in both the general and the collision-dominant regime — that transfer null is published, and it bounds the result above to the benchmark it was measured on. Every number regenerates from committed evidence. Code and evidence: [GitHub](https://github.com/manfromnowhere143/sentinel). Paper: [preprint PDF](https://github.com/manfromnowhere143/sentinel/blob/master/docs/paper/paper.pdf).

**[Telos](https://telos.danielwahnich.dev)** ~ evidence protocol and benchmark harness for checking whether autonomous coding agents actually finished the task, not just the visible test. It runs on real SWE-bench_Verified trajectories and reward-hack fixes that can fool static verifiers and frontier reward models. The current evidence is bounded but clear: held-out execution, receipts, and repair loops are needed to recover real completion. Code and evidence: [GitHub](https://github.com/manfromnowhere143/telos). No leaderboard or broad ranking claim.

**[PerceptionProof](https://github.com/manfromnowhere143/perceptionproof)** ~ do cheap label-free signals predict human-rated long-tail driving failure where open-loop metrics mis-rank closed-loop safety? A reproducible validity study with a published negative-results arc.

## Links

[danielwahnich.dev](https://danielwahnich.dev) · [aweblabs.ai](https://aweblabs.ai) · [Sentinel](https://sentinel.danielwahnich.dev) · [Telos](https://telos.danielwahnich.dev) · [LinkedIn](https://www.linkedin.com/in/daniel-wahnich-048326412)
