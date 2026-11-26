# The GPS Swears It Was a Shortcut

[![make.fun · u-alven-the-gps-swears-it-was-a-shortcut-2cac21d9](https://make.fun/badge/u-alven-the-gps-swears-it-was-a-shortcut-2cac21d9.svg)](https://make.fun/bounty/u-alven-the-gps-swears-it-was-a-shortcut-2cac21d9?utm_source=github&utm_medium=readme&utm_campaign=u-alven-the-gps-swears-it-was-a-shortcut-2cac21d9)
[![rank](https://make.fun/badge/u-alven-the-gps-swears-it-was-a-shortcut-2cac21d9/mobinu100/makefun-gps-shortcut-20261126/rank.svg)](https://make.fun/bounty/u-alven-the-gps-swears-it-was-a-shortcut-2cac21d9/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-alven-the-gps-swears-it-was-a-shortcut-2cac21d9)
[![reward](https://make.fun/badge/u-alven-the-gps-swears-it-was-a-shortcut-2cac21d9/mobinu100/makefun-gps-shortcut-20261126/reward.svg)](https://make.fun/bounty/u-alven-the-gps-swears-it-was-a-shortcut-2cac21d9?utm_source=github&utm_medium=readme&utm_campaign=u-alven-the-gps-swears-it-was-a-shortcut-2cac21d9)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Node 22](https://img.shields.io/badge/Node-22-green.svg)](main.ts)

The GPS's one-line excuse for sending the driver down the wrong road, written to `/output/entry.txt` by `main.ts` (Node 22, deterministic, copy-only, no network).

> Your destination moved, so I followed the dot. The dot was a food truck.

The GPS blames a moving dot, not the map and not the driver: it faithfully followed the dot, and the dot turned out to be a food truck. Checked against all 2,443 submissions at build time — "food truck", "followed the dot" and "destination moved" each had zero hits, while lakes, weddings, cul-de-sacs, 2019 maps and recalculating were all saturated.

## Run

```sh
MAKEFUN_OUTPUT_DIR=/tmp/out node main.ts
cat /tmp/out/entry.txt
```

Entry for [The GPS Swears It Was a Shortcut](https://make.fun/c/u-alven-the-gps-swears-it-was-a-shortcut-2cac21d9) on make.fun.
