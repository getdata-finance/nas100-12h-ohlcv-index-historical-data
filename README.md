# NAS100 12h OHLCV Index Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-10_057_rows-blue)](https://getdata.finance/datasets/nas100) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/nas100)

### -> [**Download the full NAS100 dataset on getdata.finance**](https://getdata.finance/datasets/nas100)

**NAS100 12h OHLCV index historical data** — ultra high-quality 12h OHLCV for **NASDAQ 100**. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

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

- **Ultra high-quality 12h OHLCV** for **NASDAQ 100** (Index)
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`12h`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/nas100) · **10,057** `12h` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `12h` sample updated in sync

> **Sample on GitHub** · `NAS100_12h.csv` (290 rows, `2026-03-23` -> `2026-09-23`, 25.02 KB). **Full archive on [getdata.finance](https://getdata.finance/datasets/nas100)** — **10,057** `12h` rows (full `1m`: 5,050,229), **11 timeframes**, `2009-01-02` -> `2026-09-23`.

## Download sample

**[NAS100_12h.csv](https://github.com/getdata-finance/nas100-12h-ohlcv-index-historical-data/blob/main/NAS100_12h.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/nas100-12h-ohlcv-index-historical-data/main/NAS100_12h.csv)) · [GitHub Releases](https://github.com/getdata-finance/nas100-12h-ohlcv-index-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/nas100-12h-ohlcv-index-historical-data/](https://getdata-finance.github.io/nas100-12h-ohlcv-index-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/nas100](https://getdata.finance/datasets/nas100)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/nas100))** |
|---|--:|---|
| Instrument | NASDAQ 100 · Index | NASDAQ 100 · Index |
| Timeframes | `12h` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 12h rows | 290 | **10,057** |
| Size | 25.02 KB | full ZIP on [getdata.finance](https://getdata.finance/datasets/nas100) |
| Period | `2026-03-23` -> `2026-09-23` | `2009-01-02` -> `2026-09-23` |
| File | `NAS100_12h.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/nas100) |
| Coverage report | — | [NAS100 coverage](https://getdata.finance/coverage/nas100) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`12h` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/nas100)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W**

GitHub = `12h` sample · [getdata.finance](https://getdata.finance/datasets/nas100) = all **11** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `12h` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`NAS100_12h.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-03-23T12:00:00+00:00 | 24180.42 | 24477.62 | 24099.25 | 24256.22 | 1932790 |
| 2026-03-24T00:00:00+00:00 | 24256.22 | 24305.85 | 23993.35 | 24182.72 | 1134049 |
| 2026-03-24T12:00:00+00:00 | 24182.72 | 24343.17 | 23935.87 | 24222.04 | 2081313 |
| 2026-03-25T00:00:00+00:00 | 24222.04 | 24343.04 | 24129.79 | 24304.16 | 730961 |
| 2026-03-25T12:00:00+00:00 | 24304.16 | 24348.54 | 24097.19 | 24141.54 | 1613567 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-09-21T00:00:00+00:00 | 29740.06 | 29976.31 | 29728.81 | 29957.94 | 478128 |
| 2026-09-21T12:00:00+00:00 | 29957.94 | 30577.44 | 29913.56 | 30573.06 | 924298 |
| 2026-09-22T00:00:00+00:00 | 30573.06 | 30637.31 | 30391.76 | 30497.44 | 579855 |
| 2026-09-22T12:00:00+00:00 | 30497.44 | 30800.56 | 30469.19 | 30796.19 | 1008367 |
| 2026-09-23T00:00:00+00:00 | 30796.19 | 30796.19 | 30741.19 | 30747.31 | 107835 |

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

df = pd.read_csv('NAS100_12h.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('NAS100_12h.csv', parse_dates=['datetime'])
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

df = pd.read_csv('NAS100_12h.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='12h')
print(pf.stats())
```

## Download full data

The complete **NAS100** archive on **[getdata.finance](https://getdata.finance/datasets/nas100)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **10,057** rows at `12h`, plus all other timeframes in the same ZIP.

**[-> Get the full NAS100 dataset on getdata.finance](https://getdata.finance/datasets/nas100)**

---
*GetData · NAS100 12h OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/nas100)*
