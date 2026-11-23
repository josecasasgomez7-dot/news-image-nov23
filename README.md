# News Image — 23 November 2026

[![make.fun · news-image-20261123](https://make.fun/badge/news-image-20261123.svg)](https://make.fun/bounty/news-image-20261123?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261123)
[![rank](https://make.fun/badge/news-image-20261123/josecasasgomez7-dot/news-image-nov23/rank.svg)](https://make.fun/bounty/news-image-20261123/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261123)
[![reward](https://make.fun/badge/news-image-20261123/josecasasgomez7-dot/news-image-nov23/reward.svg)](https://make.fun/bounty/news-image-20261123?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261123)

A one-page newspaper front page that sums up Monday, 23 November 2026, built for the make.fun News Image bounty ("Sum up 23 November's world news in one image", $100 in USDC). The page is plain HTML and CSS text rendered to a 1024 × 1024 PNG — no AI-generated image text, no borrowed photos.

## What's on the page

- **Lead:** Ukraine says its sea drones sank the Russian corvette Merkury at the Benghazi naval base in Libya on Sunday, and hit the cargo ship MV Angara, which it says Moscow used to carry weapons.
- **Space:** NATO intelligence believes Russia is ready to launch a nuclear-armed satellite, Sputnik-S, into space this year, German media report on Monday.
- **The Gulf:** Iran vows to use all means to counter the US naval blockade, a day after two tankers were hit near the Strait of Hormuz; President Donald Trump said on Sunday he is inclined to resume strikes after the New Year if no deal is reached.
- **Europe:** NATO's top council meets in Brussels on Monday over two suspected Russian missiles and a drone that fell in Poland on Friday.
- **Gaza:** Oxfam and the Conflict and Environment Observatory say indicators of toxic contamination cover more than 99% of Gaza, with about 78% of its land affected.
- **Indonesia (follow-up):** Indonesia confirms 24 people were killed in the candy factory fire in Cikande, Java; rescuers keep searching for dozens still missing.
- **Asia:** South Korea's education minister Choi Kyo-jin resigns over the AI-assisted cheating scandal around the college entrance exam.
- **Also today:** the aftermath of COP31's collapse, Democrats reaching 258 House seats, the Kyiv region death toll rising to 15, Russia towing the Sparta II, and Bangladesh vowing to arrest Sheikh Hasina if she returns.

Sources: Reuters, AP, CNN, Al Jazeera, AFP, Gulf News, Dawn, Oxfam and RMF24, as reported on 23 November 2026.

## How to run

```sh
MAKEFUN_OUTPUT_DIR=out node main.ts
```

`main.ts` (Node 22 stdlib only) first checks that `entry.png` is a real PNG, 1024 × 1024 and no more than 1 MiB, then writes a copy to the output directory. Without `MAKEFUN_OUTPUT_DIR` it writes to `/output`.

## Files

- `entry.png` — the finished front page (1024 × 1024)
- `main.ts` — the entry program
- `LICENSE` — MIT
