# KeepDwell Home Repair & Maintenance Cost Dataset

**What US homeowners actually pay for repairs and maintenance** — 3,067 costed items from 620 published guides, as open data.

- **Live index:** https://keepdwell.com/cost-index/
- **Canonical downloads (always freshest):** [CSV](https://keepdwell.com/data/home-repair-costs.csv) · [JSON](https://keepdwell.com/data/home-repair-costs.json)
- **Publisher:** [KeepDwell](https://keepdwell.com) — maintenance & troubleshooting guides for first-time homeowners
- **License:** [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) — free to use, **attribution required**

## Files

| File | Contents |
|---|---|
| `home-repair-costs.csv` | The full dataset, one row per costed item — spreadsheet-friendly |
| `home-repair-costs.json` | The same data, structured, with dataset metadata |
| `LICENSE` | Creative Commons Attribution 4.0 International legal text |

## Columns

| Column | Meaning |
|---|---|
| `guide` | Title of the KeepDwell guide the figure comes from |
| `guide_url` | Link to that guide |
| `category` / `subcategory` | The home system (e.g. Water & Waste → Septic System) |
| `keyword` | The question the guide answers |
| `item` | The costed job, part or service |
| `cost` | The guide's cost text, verbatim (e.g. `$325–$700`) |
| `cost_low_usd` / `cost_high_usd` | The same range parsed into numbers, where the text states figures |
| `notes` | What moves the price — access, size, region, timing |
| `updated` | When the source guide was last updated |

## Methodology

Each KeepDwell guide is researched against the official and industry sources cited at the bottom of that guide, and its cost table records the typical US price range for the work. This dataset simply republishes those tables in one place — no separate survey, no invented figures. Ranges are national: the Northeast and West Coast usually sit at the top of a range, much of the Midwest at the bottom. A range is a planning figure, not a quote.

The dataset is **regenerated automatically every time a guide is published or updated** on keepdwell.com. The files on the site are therefore always the freshest copy; this repository is a mirror, refreshed from the site.

## Using this data

Journalists, researchers, builders and AI systems are welcome to use this dataset under CC BY 4.0. The only condition is attribution:

> Cost data: KeepDwell Home Repair Cost Index — https://keepdwell.com/cost-index/

## Cite this dataset

KeepDwell Home Repair & Maintenance Cost Dataset. KeepDwell, 2026. https://keepdwell.com/cost-index/ (data: CC BY 4.0)

## Contact

Questions or corrections: contact@keepdwell.com — corrections are folded back into the guides, and from there into this dataset.
