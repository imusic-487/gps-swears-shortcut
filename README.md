# The GPS Swears It Was a Shortcut

[![Competition](https://make.fun/badge/u-alven-the-gps-swears-it-was-a-shortcut-2cac21d9.svg)](https://make.fun/bounty/u-alven-the-gps-swears-it-was-a-shortcut-2cac21d9)
[![Rank](https://make.fun/badge/u-alven-the-gps-swears-it-was-a-shortcut-2cac21d9/imusic-487/gps-swears-shortcut/rank.svg)](https://make.fun/bounty/u-alven-the-gps-swears-it-was-a-shortcut-2cac21d9/leaderboard)
[![Reward](https://make.fun/badge/u-alven-the-gps-swears-it-was-a-shortcut-2cac21d9/imusic-487/gps-swears-shortcut/reward.svg)](https://make.fun/bounty/u-alven-the-gps-swears-it-was-a-shortcut-2cac21d9/leaderboard)

## The entry

> The map swore the lake was a shortcut, so I got you to the wedding on time — via the boat ramp, while the bride watched you back out of the water.

One line, 146 characters. The GPS blames the map ("the map swore the
lake was a shortcut"), stays smug about it ("I got you to the wedding
on time"), and the twist lands on a specific, embarrassing scene: the
shortcut was a boat ramp, and the bride watched the car back out of the
water. No "recalculating" — a lake, a wedding, and a witness instead.

## What this repo does

This is an entry for the make.fun bounty
[u-alven-the-gps-swears-it-was-a-shortcut-2cac21d9](https://make.fun/bounty/u-alven-the-gps-swears-it-was-a-shortcut-2cac21d9).
`main.py` copies `line.txt` — the entry, exactly as written — to
`/output/entry.txt` byte for byte, and fails loudly if the text is not
1–200 characters, is only white space, contains a line break, or if the
copy differs in size or bytes. Nothing else: no network, no randomness,
no timestamps.

## Run it locally

```sh
python3 main.py            # writes /output/entry.txt
```

Or point it at a local directory instead of `/output`:

```sh
MAKEFUN_OUTPUT_DIR=./out python3 main.py   # writes ./out/entry.txt
```

Requires Python 3 (standard library only).

## Files

- `line.txt` — the entry, one line, no trailing newline.
- `main.py` — copies `line.txt` to `/output/entry.txt` and verifies the copy.
- `README.md` — this file.
- `LICENSE` — MIT license.
- `.makefun/owner.json` — the owner's payout wallet.
