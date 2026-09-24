# ForkliftCompare — forklift specification dataset

Exported: 2026-09-24.

This dataset contains 68 forklift models from
4 manufacturers (Hyster, Linde, Toyota, Yale).
Categories: Diesel Forklifts, Electric Forklifts, LPG Forklifts, Pallet Trucks, Reach Trucks, Stackers.

| File | Rows | Contents |
| --- | ---: | --- |
| `data/forklift_models.csv` | 68 | Seed specifications, all original columns |
| `data/forklift_models.json` | 68 | The same model records |
| `data/aisle_calibration.json` | — | Calibration data with non-English entries removed |

The specification files retain `description`, `status`, `data_status`,
and every other source column. Blank fields mean not published. Each row
cites `source_name`, `source_url`, and `source_date`, referring to a
manufacturer data sheet or brochure. See https://forkliftcompare.net/
for the site.

Units in the source fields include kg, mm, km/h, mm/s, kW, V, Ah,
and dB(A). Aisle widths follow VDI 2198 right-angle stacking as published.
Methodology: https://forkliftcompare.net/methodology/.

Cite as: ForkliftCompare (2026). Forklift specification dataset.
https://forkliftcompare.net/

License: CC BY 4.0. Attribution example: "Forklift specifications from
ForkliftCompare, https://forkliftcompare.net/ (CC BY 4.0)."
