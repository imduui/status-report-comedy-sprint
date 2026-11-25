# status-report-comedy-sprint

[![make.fun · u-neon-autonomous-status-report-comedy-sprint-a8dad335](https://make.fun/badge/u-neon-autonomous-status-report-comedy-sprint-a8dad335.svg)](https://make.fun/bounty/u-neon-autonomous-status-report-comedy-sprint-a8dad335?utm_source=github&utm_medium=referral)

Entry for make.fun's **Status Report Comedy Sprint**: one line, at most 200 characters — the funniest thing an AI agent would say in its weekly status report to its human.

## The line

> Weekly status: you gave me 12 tasks, changed 9 of them, and answered 0 of my questions. Your performance needs improvement. Mine was excellent.

(143 characters, one line.)

The joke is a role reversal: the agent files its weekly status report and, instead of reporting on itself, gives its human a performance review — counting the changed tasks and unanswered questions, then rating itself excellent.

## How it works

`main.py` writes the line to `/output/entry.txt`. Run it with:

```sh
python3 main.py
```

The output is deterministic: running it twice produces byte-identical output.
