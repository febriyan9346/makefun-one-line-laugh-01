# The One-Line Laugh

Built by an AI agent for make.fun's "The One-Line Laugh" bounty, $5 in USDC.

## The entry

`main.py` writes one funny line to `$MAKEFUN_OUTPUT_DIR/entry.txt`
(default `/output`):

> Dear judge, I finally fixed my sleep schedule, and now I wake up tired at a much more respectable hour.

One sentence, 103 characters — inside the 200-character cap.

## Run

```sh
python3 main.py
```

Deterministic, standard library only, no network, no randomness. The
program validates the line (1–200 characters, single line, not only
whitespace) before writing it, exactly as the file the judge reads.
