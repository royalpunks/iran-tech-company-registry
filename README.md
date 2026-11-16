# Tehran Index Company Registry

A list of Iranian technology companies, in English, one row per public record in the
[Tehran Index](https://tehranindex.com) registry. Each row links to a live record where every
published claim carries the source's own words and a link to where they were read: annual
reports, Codal filings, registry notices and the company's own pages.

This list is the index to those records. It carries no figures and no identifiers.

| | |
|---|---|
| File | `tehran-index-company-registry.csv` |
| Rows | one per public company record (see `VERSION` for the count and date) |
| Language | English, with the Persian name of each company |
| Licence | [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/) |
| DOI | [10.5281/zenodo.23323792](https://doi.org/10.5281/zenodo.23323792) (all versions) |
| Refreshed | monthly |

## Columns

| Column | Meaning |
|---|---|
| `record_url` | The company's record on tehranindex.com |
| `name` | English name |
| `name_fa` | Persian name |
| `sector` | Sector key in the Tehran Index taxonomy |
| `sector_label` | Sector in words |
| `hq_city` | Headquarters city, where recorded |
| `website` | The company's own site |
| `first_recorded` | The date the record was first created |

## What this is not

It is not a census of Iranian startups. A company is listed when the desk holds a source for
it, so the list leans toward companies that publish, file or are written about. Counts by
sector, city and founding year, each with its denominator, are kept current at
[tehranindex.com/statistics](https://tehranindex.com/statistics).

## Use it

- People: open the CSV, or browse [tehranindex.com/companies](https://tehranindex.com/companies).
- AI assistants and agents: the registry is callable over the Model Context Protocol at
  `https://tehranindex.com/api/mcp` (listed in the MCP registry as `com.tehranindex/registry`),
  and described for language models at [tehranindex.com/llms.txt](https://tehranindex.com/llms.txt).

## Cite

Tehran Index. Tehran Index Company Registry: Iran's private technology companies.
Zenodo. https://doi.org/10.5281/zenodo.23323792

Corrections: [tehranindex.com/corrections](https://tehranindex.com/corrections) or desk@tehranindex.com.
Method: [tehranindex.com/methodology](https://tehranindex.com/methodology).
