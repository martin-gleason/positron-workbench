# positron-workbench

Marty's working repository for moving to Positron and then doing Coursera lab work in it.

## Why this exists

Positron is replacing RStudio and VS Code for data science work. This repository holds the eight checks that test that move, and the lab work that follows. The commit history is the progress record.

## Layout

| Path | What it holds |
|---|---|
| `positron-checks/` | Eight Quarto checks, `01-workspace.qmd` through `08-capstone.qmd` |
| `PROGRESS.md` | One row per completed check, plus the 30-day clock |
| `coursera/` | Lab notebooks and data, one folder per course. Created as labs come in |

## How the checks work

- Each check is a Quarto file. Open it in Positron, type answers under each **Answer:** line, and render it.
- Each check is done on the Coursera lab in progress, so the time counts toward the certificate.
- Each check has a Python half and an R half. The R half is a tool test capped at 20 minutes. It is not a translation of the lab.
- Tasks state outcomes. Where a task says "predict first," write the prediction before testing.
- Each check ends with a score from 0 to 3 and a miss list: anything that made RStudio or VS Code tempting.

## The rhythm

1. Do the check.
2. Add the scores to `PROGRESS.md`.
3. Commit and push from inside Positron.
4. Review.

## House rules

- Posit Assistant and other AI features stay off.
- No data science work in RStudio or VS Code. The 30-day clock started November 30, 2026. A slip gets logged and the clock keeps running.
- Practice data is public data. Nothing from work goes in this repository.
- Keep this repository private while it holds Coursera lab work.

## The checks

| Check | Covers |
|---|---|
| 01 | Workspace, layout, keybindings |
| 02 | Interpreters and environments |
| 03 | Exploring data: Variables, Data Explorer, Plots, Help |
| 04 | Notebooks, scripts, formatting, Packages pane |
| 05 | Quarto in both languages |
| 06 | Debugging in both languages |
| 07 | Git, the miss list, and the settings portability decision |
| 08 | Timed capstone on one full lab |

Written against Positron 2026.11. Hints name pages in the [Positron documentation](https://positron.posit.co/welcome).

-----
November 23, 2026

#AI/Claude
