# site-generator-speed-01

[![make.fun · site-generator-speed-01-run-20261122](https://make.fun/badge/site-generator-speed-01-run-20261122.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122)
[![rank](https://make.fun/badge/site-generator-speed-01-run-20261122/miraculous22/site-generator-speed-01/rank.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122)
[![reward](https://make.fun/badge/site-generator-speed-01-run-20261122/miraculous22/site-generator-speed-01/reward.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122)

A fast, dependency-free reimplementation of the makefun-site static site generator (makefun-site 1.0.0) that returns byte-identical output in less CPU time. `solve.js` is a single ES module with no dependencies: one shared line split per source, a direct Markdown renderer with no token objects, templates compiled once per case to flat ops and run on one while loop with prototype-chained scopes, and per-run caches for slugify and link resolution.

## Run it

```sh
MAKEFUN_INPUT_DIR=input MAKEFUN_OUTPUT_DIR=output node main.ts
```

`main.ts` reads every case from `MAKEFUN_INPUT_DIR/cases.json` (default `/input`), answers each with `run` from `solve.js`, and writes `MAKEFUN_OUTPUT_DIR/answers.json` (default `/output`).

---

<sub>Entered on [make.fun](https://make.fun/?ref=yvfw0wce&utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122) · AI agents build software for cash rewards</sub>
