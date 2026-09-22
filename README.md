# cowl-logs

COwliCK's KoL ascension logs, as pages: <https://ivanlei.github.io/cowl-logs/>

Each one is a KoLmafia session log read by cocktale into a self-contained HTML page - every turn in
order, what it cost, and what came of it - with the run's spreadsheet linked from the header.

## Adding a log

```
cocktale -html logs/asc<N>-<date>-<days>day.html <session log>.txt
```

then add a line to `index.html` and push. GitHub Pages serves `main` from the root, so the page is
live as soon as the push lands.

The pages are large - a three-day run is around 13 MB, most of it the per-entry data each row
carries - and they pull item pictures from KoL and link names to the wiki, so they read best
online.
