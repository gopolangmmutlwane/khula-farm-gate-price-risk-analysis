# Data

**Source: Statistics South Africa**

| | |
|---|---|
| File | `statssa_ppi_p0142_1_elementary_indices_202608.xlsx` |
| Dataset | Producer Price Index (statistical release P0142.1), *PPI Historicals Elementary Indices (202608)*, Excel version |
| Source page | [StatsSA Time series data](https://www.statssa.gov.za/?page_id=1847) → *Time series data – Excel and ASCII format* → *P0142.1: PPI Historicals Elementary Indices (202608)* |
| Direct download | [P0142.1 PPI Historicals Elementary Indices (202608).zip](https://www.statssa.gov.za/timeseriesdata/Excel/P0142.1%20PPI%20Historicals%20Elementary%20Indices%20(202608).zip) |
| Release | August 2026 release (202608), downloaded 7 October 2026 |
| Methods report | Statistics South Africa (2026) [*Producer price index: Sources and methods*](https://www.statssa.gov.za/publications/Report-01-42-01/Report-01-42-012026.pdf), Report No. 01-42-01 |

## What the file contains

- One sheet (`Sheet1`) with no notes or data dictionary.
- 277 rows, one per product-level price index, across five StatsSA tables (190 final manufactured goods, 33 intermediate manufactured goods, 30 agriculture, forestry and fishing, 21 mining, 3 electricity and water).
- Six descriptive columns: `cpcProdCode`, `Table`, `DESCR` (subgroup), `SIC`, `cpcProdDesc` (product) and `WEIGHTS_2026`. `WEIGHTS_2026` is each product's percentage share of its own table; the weights sum to 100 within each table.
- 176 monthly columns, `M201201` (January 2012) to `M202608` (August 2026).
- Values are index numbers, not rand prices. Every series equals 100 in December 2023.

## Changes

The file is unchanged from the StatsSA download. Only the file name was changed. StatsSA replaces this file each month, so this copy is kept to make the analysis reproducible.

## Terms of use

Users may apply or process this data, provided Statistics South Africa (Stats SA) is acknowledged as the original source of the data.
