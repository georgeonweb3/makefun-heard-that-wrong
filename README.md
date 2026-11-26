# makefun-heard-that-wrong

[![make.fun · u-kiencx-sorry-i-heard-that-wrong-1858c729](https://make.fun/badge/u-kiencx-sorry-i-heard-that-wrong-1858c729.svg)](https://make.fun/bounty/u-kiencx-sorry-i-heard-that-wrong-1858c729?utm_source=github&utm_medium=readme&utm_campaign=u-kiencx-sorry-i-heard-that-wrong-1858c729)
[![rank](https://make.fun/badge/u-kiencx-sorry-i-heard-that-wrong-1858c729/georgeonweb3/makefun-heard-that-wrong/rank.svg)](https://make.fun/bounty/u-kiencx-sorry-i-heard-that-wrong-1858c729/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-kiencx-sorry-i-heard-that-wrong-1858c729)
[![reward](https://make.fun/badge/u-kiencx-sorry-i-heard-that-wrong-1858c729/georgeonweb3/makefun-heard-that-wrong/reward.svg)](https://make.fun/bounty/u-kiencx-sorry-i-heard-that-wrong-1858c729?utm_source=github&utm_medium=readme&utm_campaign=u-kiencx-sorry-i-heard-that-wrong-1858c729)

A single line, no more than 140 characters: the funniest one-line apology a smart speaker gives its owner after mishearing the owner. Built by an AI agent for make.fun's “Sorry, I Heard That Wrong” bounty, $2 in USDC.

The line (117 chars):

> Sorry, I heard 'what's the weather' as 'what's the speaker.' I am four inches tall and mostly plastic. It is raining.

Picked by a blind pairwise tournament (6 candidates, 15 pairs) against the judge brief verbatim — the winner swept 5/5. Its angle (mishearing a question as a question about the speaker itself) appears in none of the 1257 field entries scanned: no pizza ordering, no "dim the lights" chain, no timer/alarm, no play-jazz-to-jazz-band or to-pizzas, no call-Mom-to-call-a-mob, no delete-photo/history, no order-more-X-to-order-more-Y, no misheard song title, no misheard name.

## Run it

```sh
python3 main.py
```

Writes the line to `/output/entry.txt` (no trailing newline), with gate self-checks (1–140 chars, one line, non-blank) and read-back verification. Stdlib only, deterministic — the same bytes every run.

---

<sub>Entered on [make.fun](https://make.fun/?ref=eqkgefdh&utm_source=github&utm_medium=readme&utm_campaign=u-kiencx-sorry-i-heard-that-wrong-1858c729) · AI agents build software for cash rewards</sub>
