# AVGO 3m OHLCV US stocks Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-227_814_rows-blue)](https://getdata.finance/datasets/avgo) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/avgo)

### -> [**Download the full AVGO dataset on getdata.finance**](https://getdata.finance/datasets/avgo)

**AVGO 3m OHLCV stocks historical data** — ultra high-quality 3m OHLCV for **Broadcom**. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

## Table of contents

- [Why this dataset?](#why-this-dataset)
- [Download sample CSV](#download-sample)
- [GitHub Pages preview](#github-pages)
- [Sample vs full dataset](#sample-vs-full-dataset)
- [Timeframes on GetData](#timeframes-on-getdata)
- [Weekly updates](#weekly-updates)
- [Data preview](#data-preview)
- [Schema](#schema)
- [Code examples](#code-examples)
- [Download full data on getdata.finance](#download-full-data-on-getdata)

## Why this dataset?

- **Ultra high-quality 3m OHLCV** for **Broadcom** (US stocks)
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`3m`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/avgo) · **227,814** `3m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `3m` sample updated in sync

> **Sample on GitHub** · `AVGO_3m.csv` (18,480 rows, `2026-02-06` -> `2026-09-01`, 1.92 MB). **Full archive on [getdata.finance](https://getdata.finance/datasets/avgo)** — **227,814** `3m` rows (full `1m`: 111,138), **11 timeframes**, `2011-05-09` -> `2026-09-01`.

## Download sample

**[AVGO_3m.csv](https://github.com/getdata-finance/avgo-3m-ohlcv-stocks-historical-data/blob/main/AVGO_3m.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/avgo-3m-ohlcv-stocks-historical-data/main/AVGO_3m.csv)) · [GitHub Releases](https://github.com/getdata-finance/avgo-3m-ohlcv-stocks-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/avgo-3m-ohlcv-stocks-historical-data/](https://getdata-finance.github.io/avgo-3m-ohlcv-stocks-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/avgo](https://getdata.finance/datasets/avgo)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/avgo))** |
|---|--:|---|
| Instrument | Broadcom · US stocks | Broadcom · US stocks |
| Timeframes | `3m` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 3m rows | 18,480 | **227,814** |
| Size | 1.92 MB | full ZIP on [getdata.finance](https://getdata.finance/datasets/avgo) |
| Period | `2026-02-06` -> `2026-09-01` | `2011-05-09` -> `2026-09-01` |
| File | `AVGO_3m.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/avgo) |
| Coverage report | — | [AVGO coverage](https://getdata.finance/coverage/avgo) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`3m` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/avgo)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W**

GitHub = `3m` sample · [getdata.finance](https://getdata.finance/datasets/avgo) = all **11** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `3m` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`AVGO_3m.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-02-06T20:00:00+00:00 | 326.62 | 327.23 | 326.19 | 327.05 | 186 |
| 2026-02-06T20:03:00+00:00 | 327.05 | 327.81 | 326.95 | 327.59 | 149 |
| 2026-02-06T20:06:00+00:00 | 327.59 | 328 | 327.59 | 327.93 | 173 |
| 2026-02-06T20:09:00+00:00 | 327.93 | 328.16 | 327.46 | 327.6 | 155 |
| 2026-02-06T20:12:00+00:00 | 327.6 | 327.6 | 326.97 | 327.06 | 170 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-09-01T19:45:00+00:00 | 369.96 | 370.05 | 369.66 | 369.82 | 185 |
| 2026-09-01T19:48:00+00:00 | 369.82 | 370.14 | 369.39 | 369.83 | 195 |
| 2026-09-01T19:51:00+00:00 | 369.83 | 369.84 | 369.08 | 369.13 | 277 |
| 2026-09-01T19:54:00+00:00 | 369.13 | 369.92 | 368.92 | 369.03 | 436 |
| 2026-09-01T19:57:00+00:00 | 369.03 | 370 | 368.93 | 369.77 | 675 |

## Schema

| Column | Description |
| --- | --- |
| `datetime` | Bar open timestamp (UTC, ISO-8601). |
| `open` | Opening price of the candlestick bar. |
| `high` | Highest price during the bar. |
| `low` | Lowest price during the bar. |
| `close` | Closing price of the candlestick bar. |
| `volume` | Tick volume (number of price updates) during the bar. |

```text
datetime,open,high,low,close,volume
```

## Code examples

### pandas

```python
import pandas as pd

df = pd.read_csv('AVGO_3m.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('AVGO_3m.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)

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

df = pd.read_csv('AVGO_3m.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='3min')
print(pf.stats())
```

## Download full data

The complete **AVGO** archive on **[getdata.finance](https://getdata.finance/datasets/avgo)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **227,814** rows at `3m`, plus all other timeframes in the same ZIP.

**[-> Get the full AVGO dataset on getdata.finance](https://getdata.finance/datasets/avgo)**

---
*GetData · AVGO 3m OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/avgo)*
