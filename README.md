# r-lang

R in language research (linguistics), 2007 to 2009

This copy is kept as it was collected and is no longer updated. The list's whole history, 2007 to 2019, is in [gmane-archive](https://github.com/r-mailing-lists/gmane-archive/tree/main/r-lang), read from Gmane's news server, and that is the copy the R Mailing List Archives show. This repository holds what the list's first archive at UC San Diego still served in October 2026.

## Structure

- `raw/` - Monthly .mbox files downloaded from [http://pidgin.ucsd.edu/pipermail/r-lang/](http://pidgin.ucsd.edu/pipermail/r-lang/)
- `processed/` - Structured JSON output from rmail-parser
- `sources/` - Where present, each message's page at the source and the characters that page restores, one JSON file per period
- `attachments/` - Text Mailman scrubbed out of messages, fetched once from the source and put back by rmail-parser, one gzip-compressed JSON file per period
- `meta.json` - List statistics

## Viewer

Browse these archives at [archives.rstats.dev](https://archives.rstats.dev/lists/r-lang/)
