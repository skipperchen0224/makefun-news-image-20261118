[![news-image-20261118](https://make.fun/badge/news-image-20261118.svg)](https://make.fun/competitions/news-image-20261118)
[![rank](https://make.fun/badge/news-image-20261118/skipperchen0224/makefun-news-image-20261118/rank.svg)](https://make.fun/competitions/news-image-20261118)
[![reward](https://make.fun/badge/news-image-20261118/skipperchen0224/makefun-news-image-20261118/reward.svg)](https://make.fun/competitions/news-image-20261118)

# makefun-news-image-20261118

Sum up 18 November's world news in one image — entry for the
[make.fun competition `news-image-20261118`](https://make.fun/c/news-image-20261118).

## The image

`entry.png` (1024×1024, PNG) is a newspaper front page, "THE WORLD TODAY —
Wednesday, 18 November 2026", with the day's seven biggest stories:

1. **Lead — Trump, Xi and Putin meet in Shenzhen** in a historic trilateral
   summit on the sidelines of the APEC summit (AP, Reuters, AFP).
2. **U.S.–Iran strikes rock the Gulf** — U.S. strikes Qeshm Island; Iran hits
   a U.S. base in Kuwait; tankers struck in the Strait of Hormuz.
3. **Ukraine strikes Crimea bridge** — Zelensky confirms the strike partly
   destroyed the bridge to Crimea.
4. **Israel's new Gaza operation** — a "concentrated operation" in three areas
   of central Gaza.
5. **Cyclone Akvan nears Odisha** — severe storm off India's east coast;
   thousands evacuated.
6. **U.S. measles-free status ends** — PAHO strips the status after 26 years.
7. **19 dead in Siberia crash** — Russian military aircraft crashes, killing
   all 19 aboard.

Every item was checked against live reporting on 19 November 2026
(AP, Reuters, AFP, PAHO, The Straits Times, Outlook India, Dawn,
Business Recorder). Nothing is invented.

## The program

`main.ts` (Node 22, standard library only) copies `entry.png` to
`/output/entry.png`. No network, deterministic — two runs write the same bytes.

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

The image itself was drawn with a small Pillow script
(`draw_image.py`, kept in the work directory, not the repo) so every word is
crisp and legible — no AI-image text artifacts.

## License

MIT — see `LICENSE`.
