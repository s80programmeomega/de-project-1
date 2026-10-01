# de-project-1

> Status: Week 0 — skeleton only. Sections below are filled in as the 12-week plan progresses.

## Overview
_One paragraph: what this project does, the data domain, and the question it answers. (Fill in by Week 4.)_

## Data model
_Fill in Week 4._
- **Grain:** one row in the fact table represents …
- **ER diagram:** `docs/images/er-diagram.png`
- **Layers:** bronze (raw) → silver (cleaned) → gold (star schema)
- **Performance notes:** see `docs/performance-notes.md`

## How to run
_Fill in Week 5, update in Weeks 6–8._
```bash
cp .env.example .env      # then set real values locally; never commit .env
docker compose up -d      # Postgres (Airflow added in Week 6)
```

## Architecture
_Diagram and short walkthrough: source → raw → load → dbt marts → orchestration. (Fill in Week 8.)_

## Failure policy
_Fill in Week 8._

| Check | Where | On failure |
|---|---|---|
| | | stop pipeline / quarantine + alert |

## Design decisions
_Short entries: what you chose, what you rejected, why._

## Limitations and next steps
_Be honest about what this does not handle yet._
