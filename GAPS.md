# What this repository does not hold — 111th Congress

The 111th Congress sat from 2009-01-03 to 2011-01-02.

## Coverage

| Edition | Branch | Issue days | Documents | First | Last |
|---|---|---|---|---|---|
| Daily edition (CREC) | `daily` | 363 | 61,902 | 2009-01-06 | 2010-12-29 |
| Bound edition (CRECB) | `bound` | 373 | 50,515 | 2009-01-03 | 2010-12-29 |

Every figure above is read back out of the branch itself, not counted by
the run that wrote it — so this table describes the repository as it
stands, and a re-run that finds everything already built renders it
identically and commits nothing.

## Packages that could not be read

govinfo listed these and this build could not retrieve their contents,
so the issue days inside them have no commit:

- `CREC-2009-10-28`
- `CREC-2009-10-29`
- `CREC-2009-10-30`
- `CREC-2009-12-07`
- `CREC-2009-12-09`
- `CREC-2010-02-08`
- `CREC-2010-03-08`
- `CREC-2010-03-16`
- `CREC-2010-03-17`

## What this repository is not

The Record is a record of *proceedings*, not of outcomes. It reports what
was said and what was laid before each chamber; how each member voted is
not derivable from it, and the text of a measure is not here either.

Measures named in a document are cross-referenced by citation in that
document's front matter. The text of each one is a branch in
[`us-congress-bills-111`](https://github.com/junxit/us-congress-bills-111).
