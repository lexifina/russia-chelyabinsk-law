<!-- lawwatch: written from data/checks by the check trail; edit the records, not this page -->

# Monitoring: what is read and what came of it

How global-law monitors every country: [global-law monitoring/](https://github.com/lexifina/global-law/tree/main/monitoring). This page is the same for Chelyabinsk Oblast only: every time an official source is read, when, and what came of it (acts added, changed and removed). The machine-readable form is [data/checks/](../data/checks/) (JSON Lines, schema `lexifina-check/1`), in `git log` as `Kind: check` commits, and month by month in [checks/](checks/).

**Last check:** 2026-11-24 13:24 UTC, Chelyabinsk Oblast: Official Internet Portal of Legal Information (region74): 20 addresses read; 28 added, 0 changed, 0 removed; changes found; 0 not published, 0 of them with no reason.

## Sources

| Source | Folders | How often | Last successful check | Last result | State |
| --- | --- | --- | --- | --- | --- |
| [Chelyabinsk Oblast: Official Internet Portal of Legal Information (region74)](http://publication.pravo.gov.ru/documents/block/region74) | `zakony-<year>/` | daily | 2026-11-24 13:24 UTC | changes found | watched |

## The last 30 days

| Started (UTC) | Source | Read | Added | Changed | Removed | Not published (no reason) | Result | Commits |
| --- | --- | ---: | ---: | ---: | ---: | ---: | --- | ---: |
| [2026-11-24 13:10](checks/2026-11.md#ru-pravo-chelyabinsk-20261124t131026z) | pravo-chelyabinsk | 20 | 28 | 0 | 0 | 0 (0) | changes found | [6](https://github.com/lexifina/russia-chelyabinsk-law/compare/bf738a46433f...551d07a3ec19) |

## Check it yourself

```
python tools/checktrail.py                      # the latest check of every source
python tools/checktrail.py --day 2026-11-23     # every check of a day
python tools/checktrail.py --act <id>           # when an act was seen and published
git log --grep='^Kind: check' --format='%ci %s'  # the checks in the history
```

Only the official publication has legal force; the texts here are copies for reading and searching.
