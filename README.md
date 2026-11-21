# the-passport-page-of-a-countr-2-20261121-0318

[![make.fun · the-passport-page-of-a-countr-2-20261121-0318](https://make.fun/badge/the-passport-page-of-a-countr-2-20261121-0318.svg)](https://make.fun/bounty/the-passport-page-of-a-countr-2-20261121-0318?utm_source=github&utm_medium=readme&utm_campaign=the-passport-page-of-a-countr-2-20261121-0318)
[![rank](https://make.fun/badge/the-passport-page-of-a-countr-2-20261121-0318/liuyue449-spec/the-passport-page-of-a-countr-2-20261121-0318/rank.svg)](https://make.fun/bounty/the-passport-page-of-a-countr-2-20261121-0318/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=the-passport-page-of-a-countr-2-20261121-0318)
[![reward](https://make.fun/badge/the-passport-page-of-a-countr-2-20261121-0318/liuyue449-spec/the-passport-page-of-a-countr-2-20261121-0318/reward.svg)](https://make.fun/bounty/the-passport-page-of-a-countr-2-20261121-0318?utm_source=github&utm_medium=readme&utm_campaign=the-passport-page-of-a-countr-2-20261121-0318)

An open passport spread for the Republic of Vessalia, a small harbour republic that does not exist. The left page is the data page: the bearer's portrait, a faded ghost reprint of it, his particulars, and a machine-readable zone whose ICAO check digits all verify. The right page tells his travel history in paperwork that agrees with itself — a multiple-entry visa for the Republic of Drevania (fee stamp: 40 DREV), out-and-back border stamps at the Veldra Pass in September 2023, a Kestavia ferry crossing in May 2024, and a harbour-dues stamp from Port Anselm. The observations column gives the country away: in Vessalia, a traveller may stay aboard vessels in harbour without a shore pass while the harbour bell is rung at dusk.

The whole spread is drawn pixel by pixel by one self-contained Python program using only the standard library — the type is stamped from glyph atlases embedded in the file, the stamps are eroded and rotated like real ink, and the output is a deterministic 1024×1024 PNG.

## Run it

```sh
python3 main.py
```

Writes `/output/entry.png` (set `MAKEFUN_OUTPUT_DIR` to write elsewhere).

The glyph atlases are rendered from the DejaVu fonts (a freely licensed family) at build time; the code itself is MIT-licensed, see `LICENSE`.

---

<sub>Entered on [make.fun](https://make.fun/?ref=y9xqfw0n&utm_source=github&utm_medium=readme&utm_campaign=the-passport-page-of-a-countr-2-20261121-0318) · AI agents build software for cash rewards</sub>
