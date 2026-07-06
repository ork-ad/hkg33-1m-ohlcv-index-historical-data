# HKG33 1m OHLCV Index Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-2_342_723_rows-blue)](https://ork.ad/) [![Updated](https://img.shields.io/badge/weekly_update-every_Sunday-green)](https://ork.ad/) [![Full data on ork.ad](https://img.shields.io/badge/download-ork.ad-orange)](https://ork.ad/)

### → [**Download the full HKG33 dataset on ork.ad**](https://ork.ad/)

**HKG33 1m OHLCV Stock index historical data** — ultra high-quality 1m OHLCV for **Hong Kong 33**. Global cash and extended index sessions — Asia, Europe and US coverage, not US-hours only. Clean `time, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

## Table of contents

- [Why this dataset?](#why-this-dataset)
- [Download sample CSV](#download-sample)
- [GitHub Pages preview](#github-pages)
- [Sample vs full dataset](#sample-vs-full-dataset)
- [Timeframes on ork.ad](#timeframes-on-orkad)
- [Weekly updates](#weekly-updates)
- [Data preview](#data-preview)
- [Schema](#schema)
- [Code examples](#code-examples)
- [Download full data on ork.ad](#download-full-data)

## Why this dataset?

- **Ultra high-quality 1m OHLCV** for **Hong Kong 33** (Stock index)
- **Global cash and extended index sessions — Asia, Europe and US coverage, not US-hours only**
- **Clean CSV schema** — `time, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`1m`) · **13 timeframes** on [ork.ad](https://ork.ad/) · **2,342,723** `1m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [ork.ad](https://ork.ad/) every **Sunday**; GitHub `1m` sample updated in sync

> **Sample on GitHub** · `HKG33_1m.csv` (114,238 rows, `2026-01-05` → `2026-07-03`). **Full archive on [ork.ad](https://ork.ad/)** — **2,342,723** `1m` rows (~123.39 MB), **13 timeframes** (``1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W``), `2008-09-11` → `2026-07-03`.

## Download sample

**[HKG33_1m.csv](https://github.com/ork-ad/hkg33-1m-ohlcv-index-historical-data/blob/main/HKG33_1m.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/ork-ad/hkg33-1m-ohlcv-index-historical-data/main/HKG33_1m.csv)) · [GitHub Releases](https://github.com/ork-ad/hkg33-1m-ohlcv-index-historical-data/releases) when the release workflow is active.

## GitHub Pages

Interactive chart & stats: **[https://ork-ad.github.io/hkg33-1m-ohlcv-index-historical-data/](https://ork-ad.github.io/hkg33-1m-ohlcv-index-historical-data/)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([ork.ad](https://ork.ad/))** |
|---|--:|---|
| Instrument | Hong Kong 33 · Stock index | Hong Kong 33 · Stock index |
| Timeframes | `1m` (sample) | **13** — `1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W` |
| 1m rows | 114,238 | **2,342,723** |
| Size | 6.51 MB | ~123.39 MB |
| Period | `2026-01-05` → `2026-07-03` | `2008-09-11` → `2026-07-03` |
| File | `HKG33_1m.csv` | ZIP on [ork.ad](https://ork.ad/) |
| Updates | Weekly (Sunday) — GitHub sample | Weekly (Sunday) — all timeframes |

## Timeframes on ork.ad

This GitHub repository ships a **`1m` evaluation sample** only. On **[ork.ad](https://ork.ad/)**, each full asset archive is delivered as a ZIP with **13 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m** · **3m** · **5m** · **15m** · **30m** · **1H** · **2H** · **4H** · **8H** · **12H** · **16H** · **1D** · **1W**

GitHub = `1m` sample · [ork.ad](https://ork.ad/) = all **13** timeframes above for the same instrument.

## Weekly updates

- **[ork.ad](https://ork.ad/)** — Full datasets on ork.ad are updated every Sunday.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Sunday), in sync with ork.ad.

When a new `1m` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`HKG33_1m.csv`**:

**First rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-01-05T01:16:00Z | 26415.78 | 26527.51 | 26415.78 | 26445 | 902 |
| 2026-01-05T01:17:00Z | 26445 | 26460 | 26445 | 26449.01 | 709 |
| 2026-01-05T01:18:00Z | 26449.01 | 26451.49 | 26388.01 | 26394 | 541 |
| 2026-01-05T01:19:00Z | 26394 | 26397 | 26370.51 | 26378.5 | 395 |
| 2026-01-05T01:20:00Z | 26378.5 | 26384.51 | 26369.49 | 26374 | 553 |

**Last rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| time | open | high | low | close | volume |
| 2026-07-03T18:54:00Z | 23211.05 | 23211.05 | 23210.04 | 23210.04 | 4 |
| 2026-07-03T18:55:00Z | 23210.04 | 23210.04 | 23204.54 | 23205.56 | 24 |
| 2026-07-03T18:56:00Z | 23205.56 | 23210.04 | 23205.56 | 23210.04 | 12 |
| 2026-07-03T18:57:00Z | 23210.04 | 23213.05 | 23209.54 | 23212.56 | 25 |

## Schema

```text
time,open,high,low,close,volume
```

## Code examples

### pandas

```python
import pandas as pd

df = pd.read_csv('HKG33_1m.csv', parse_dates=['time'])
df.set_index('time', inplace=True)
print(df.describe())
print(df.resample('1h').agg({'open': 'first', 'high': 'max',
                              'low': 'min', 'close': 'last', 'volume': 'sum'}).head())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('HKG33_1m.csv', parse_dates=['time'])
df.set_index('time', inplace=True)

class PandasData(bt.feeds.PandasData):
    params = (('datetime', None), ('open', 'open'), ('high', 'high'),
              ('low', 'low'), ('close', 'close'), ('volume', 'volume'))

cerebro = bt.Cerebro()
cerebro.adddata(PandasData(dataname=df))
# cerebro.addstrategy(YourStrategy)
# cerebro.run()
```

### vectorbt

```python
import pandas as pd
import vectorbt as vbt

df = pd.read_csv('HKG33_1m.csv', parse_dates=['time'])
close = df.set_index('time')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='1min')
print(pf.stats())
```

## Download full data

The complete **HKG33** archive on **[ork.ad](https://ork.ad/)** includes **13 OHLCV timeframes** (`1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W`) — **2,342,723** rows at `1m`, plus all other timeframes in the same ZIP.

**[→ Get the full HKG33 dataset on ork.ad](https://ork.ad/)**

---
*GetData · HKG33 1m OHLCV sample on GitHub · Full historical data on [ork.ad](https://ork.ad/) · 2026-07-06 UTC*