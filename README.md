# A04 - TOC and Handover Tracker

Live document-control tracker for **KAFD Parcel A04 — Main and Extension Works**.

Built from four SBCM trackers: the Main Log, the WIR & MIR Log, the Shop
Drawing Log and the As-Built Drawing Tracker.

## Files

| File | Purpose |
|---|---|
| `index.html` | The whole tracker — one self-contained page. This is the site. |
| `robots.txt` | Asks search engines not to index the page. |

## Publishing

GitHub Pages serves `index.html` at the repository root automatically.
Settings → Pages → Deploy from a branch → `main` → `/ (root)`.

## Updating the figures

The published page carries the data as of **10 September 2026**
(542 documents, 649 submissions). A viewer can drop newer trackers into
"Update from trackers" to re-read them, but that changes only their own
browser — the published figures are unchanged.

To move the published figures forward, replace `index.html` with a newly
generated copy and commit. GitHub Pages redeploys within a minute.

## Note on visibility

A public repository makes this file readable by anyone, and the page lists
every document reference, description and approval code. Keep the repository
private (GitHub Pro or above is required for Pages on a private repo) if that
is not intended.
