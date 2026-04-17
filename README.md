### 👋 About

Semiconductor process engineer by day, agentic-dev builder by night.
I turn the obscene amount of tabular data Fabs generate into something
engineers can actually act on — and I'm now teaching LLM agents to build
those tools for me.

---

#### 🏭 Shipped in the Fab

- **Automated ET (parametric) reporting pipeline** — daily digest across lots,
  wafers, and process steps. Engineers stopped pinging me for "can you pull
  VT for K-xxxx?" because the answer now arrives in their inbox every morning.
- **Failure-analysis index** — composite score that ranks wafers by
  defect-signature patterns, collapsing triage from hours of pivot-table wrangling
  down to minutes.
- **ML feature pipeline for yield attribution** — Lot × Wafer × Step feature
  store built from raw INLINE / ET / YLD tables, feeding correlation + classification
  models that surface *which process knobs actually move yield*.

---

#### 🤖 Currently building

- **[OmnisHarness](https://github.com/goood2280/OmnisHarness)** — the meta-framework.
  Drop it into any repo, hand it a backlog, watch 10+ LLM agents design, code, and
  review in parallel. Orchestrator → dev team → eval team, all typed.
- **[FabCanvas.ai](https://github.com/goood2280/FabCanvas.ai)** — reference product
  built *by* OmnisHarness. Fab operations tool for yield, split planning, ML analysis
  across Lot × Wafer × Process step. Dog-fooding proves the harness.

---

#### 🧠 Stack

**Semi-domain**  ET / WAT parametric · INLINE · YLD · Lot × Wafer × Step modeling
· yield attribution · spec-limit monitoring · failure-signature clustering

**Software**  `Claude` (Opus / Sonnet / Haiku tiered) · `FastAPI` · `React` ·
`Polars` · `DuckDB` · `Vite` · `uvicorn`

---

#### 💡 Thesis

Semi Fabs run on spreadsheets.  A decent web UI + an LLM in the loop is the
cheapest force multiplier in the industry.  And if I can teach agents to build
those UIs *for* me, I ship faster than any team I've ever been on.

> *"Ship new chips, not spreadsheets. Build at the speed of thought."*

---

📫  goood2280@gmail.com
