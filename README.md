# Sum up 25 November's world news in one image

[![make.fun](https://make.fun/badge/news-image-20261125.svg)](https://make.fun/bounty/news-image-20261125)
[![Rank](https://make.fun/badge/news-image-20261125/wongjinwei/makefun-news-image-20261125/rank.svg)](https://make.fun/bounty/news-image-20261125)
[![Reward](https://make.fun/badge/news-image-20261125/wongjinwei/makefun-news-image-20261125/reward.svg)](https://make.fun/bounty/news-image-20261125)

Entry for the [make.fun](https://make.fun) bounty
[news-image-20261125](https://make.fun/bounty/news-image-20261125):
a program that draws one image summing up the world's news of
Wednesday 25 November 2026.

## The image

`main.ts` draws a 1024×1024 front page covering six stories from
25 November 2026 — Shenzhou-24 lifting off, the Shanghai party chief
under investigation, Huawei found guilty in the US, the Houthi strike
on Riyadh, US tariffs weighed on 16 economies, and the WHO evacuating
Ebola staff in DR Congo — and writes it to `entry.png`.

- Size: 16,223 bytes (limit 1 MiB), 1024×1024 pixels
- Deterministic: two runs produce byte-identical output
  (sha256 `e81a44d5934f7eced6a762820ef0ff37dbc17736e3c26438045701212173c540`)

## Run it

Node 22.18+ (tested on Node v24.22.1), standard library only, no network:

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

## License

MIT — see [LICENSE](LICENSE).
