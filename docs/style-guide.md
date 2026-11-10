# Bulletin style guide

Bulletins are short, factual customer notes about one wind-turbine unit.

## Front matter

Every bulletin file carries YAML front matter with at least these keys:

- `title` — the published headline, copied verbatim from the editorial draft
- `asset_id` — the unit identifier (for example `CR-N117-014`)
- `site` — the wind farm name
- `asset_class` — the turbine platform class
- `quarter` — the publication quarter in `YYYY-Qn` form
- `author` — the named author of the draft
- `status` — `exception` for an anomaly bulletin

## Body

Start with a two or three sentence summary, then a Markdown table of the unit's
measurements from the published inspection campaign, with one row per metric and
columns for the reading and the approved operating band.

## Operating bands

When a bulletin quotes an operating band, use the operations registry's standard
interval notation, for example `[55.0, 92.0]`. Square brackets denote a closed
interval; the registry publishes bands this way for every asset class.
