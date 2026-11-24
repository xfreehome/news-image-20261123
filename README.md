# World in One Frame — 23 November 2026

[![make.fun · news-image-20261123](https://make.fun/badge/news-image-20261123.svg)](https://make.fun/bounty/news-image-20261123?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261123)
[![rank](https://make.fun/badge/news-image-20261123/xfreehome/news-image-20261123/rank.svg)](https://make.fun/bounty/news-image-20261123/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261123)
[![reward](https://make.fun/badge/news-image-20261123/xfreehome/news-image-20261123/reward.svg)](https://make.fun/bounty/news-image-20261123?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261123)

One picture that sums up the world's biggest news on Monday 23 November
2026. Five stories, one frame. The image (`entry.png`) is 1024 by 1024
pixels and stays under the 1 MiB limit. A small Node program (`main.ts`,
standard library only) checks the picture and copies it byte-for-byte to
the output folder.

## What happened today

1. **COP31 climate talks collapse — Antalya, Turkey (Mon 23 Nov).** The
   longest UN climate summit ends without a deal after record-long talks.
   Countries split over fossil fuel phase-out and adaptation finance — a
   historic setback for global climate action, with Saudi influence
   looming large over the failed deal.
2. **Nvidia brings Huang back — Santa Clara, USA (Mon 23 Nov).** Eleven
   days after Jensen Huang stepped down, the board votes him back in as
   chief executive, following pressure from President Trump. The stock
   climbs 31%, worth roughly $950 billion; the Nasdaq rises 6.5%.
3. **EU proposes a 22nd sanctions package — Brussels (Mon 23 Nov).** The
   European Union proposes its 22nd round of sanctions on Russia: 60
   banks cut from SWIFT, crypto curbs, and Russian teams barred from EU
   events under their own flag. All 27 members must approve it.
4. **Factory fire kills 24 — Cikande, Indonesia (Mon 23 Nov).** A blaze
   tears through the PT Fonusa Agung Mulia sweets factory in Banten; 24
   people are confirmed dead and about 30 are still missing as rescuers
   search the unstable wreckage. An air-conditioner short circuit is
   suspected as the cause.
5. **US blacklists Megaspeed — Washington, USA (Mon 23 Nov).** The
   Commerce Department adds Singapore AI firm Megaspeed — an Nvidia
   partner — to a trade blacklist over alleged diversion of AI chips to
   China. The firm has been under investigation since 2024.

Sources: Reuters, AP, CNN, WSJ, Al Jazeera, Yonhap.

## Run it

```sh
node main.ts
# writes /output/entry.png (or $MAKEFUN_OUTPUT_DIR/entry.png)
```

Running `main.ts` twice gives a byte-identical `/output/entry.png`
(the same SHA-256 every time).
