# Dataframe: `rileykhaas/finm32900_hw4_fedwatch:fed_funds_futures` - 30-Day Fed Funds Futures Daily Bars (Databento)

Daily bars from Databento's GLBX.MDP3 dataset (schema `ohlcv-1d`,
parent symbol `ZQ.FUT`). Includes outright monthly contracts and calendar
spreads; filter with `fedwatch.filter_outright_contracts`. Prices are in index
points; the implied average fed funds rate for a contract month is 100 minus
the price. Refresh with `doit forget pull && doit`.


## DataFrame Glimpse

```
Rows: 11965
Columns: 7
$ date   <datetime[ns]> 2026-09-14 00:00:00
$ symbol          <str> 'ZQU6'
$ open            <f64> 96.27
$ high            <f64> 96.2725
$ low             <f64> 96.26
$ close           <f64> 96.26
$ volume          <u64> 56538


```

## Dataframe Manifest

| Dataframe Name                 | 30-Day Fed Funds Futures Daily Bars (Databento)                                                          |
|--------------------------------|--------------------------------------------------------------------------------------|
| Dataframe ID                   | [fed_funds_futures](../dataframes/rileykhaas--finm32900_hw4_fedwatch/fed_funds_futures.md)                                       |
| Sources                        |                                           |
| Providers                      |                                         |
| Provider Links                 |                                    |
| Tags                           | Monetary Policy, Futures, Databento                                             |
| Access Types                   |                                       |
| How is data pulled?            | Databento Historical API via src/pull_fed_funds_futures.py (cost-guarded)                                                   |
| Data available up to (min)     | 2026-09-14 00:00:00                                                             |
| Data available up to (max)     | 2026-09-14 00:00:00                                                             |
| Dataframe Path                 | /home/runner/work/finm32900-hw4-fedwatch/finm32900-hw4-fedwatch/_data/fed_funds_futures.parquet                                             |


**Linked Charts:**


- [rileykhaas/finm32900_hw4_fedwatch:fedwatch_latest_forecast](../../charts/rileykhaas--finm32900_hw4_fedwatch.fedwatch_latest_forecast.md)



## Pipeline Manifest

| Pipeline Name                   | HW 4 - FedWatch Monitor                       |
|---------------------------------|--------------------------------------------------------|
| Pipeline ID                     | [rileykhaas/finm32900_hw4_fedwatch](../../../index.md)              |
| Maintainer                      | Jeremiah Bejarano               |
| Contributors                    | Jeremiah Bejarano |
| Repository                     |                   |
| Pipeline Web Page               | <a href="file:///home/runner/work/finm32900-hw4-fedwatch/finm32900-hw4-fedwatch/docs/index.html">Pipeline Web Page      |
| Date of Last Code Update        | 2026-09-15 13:24:32           |
| OS Compatibility                | Windows, Linux, macOS |
| Linked Dataframes               |  [rileykhaas/finm32900_hw4_fedwatch:fed_funds_futures](../../dataframes/rileykhaas--finm32900_hw4_fedwatch/fed_funds_futures.md)<br>  |


**Build Commands:**
```
doit

```

