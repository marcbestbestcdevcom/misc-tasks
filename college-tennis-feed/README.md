# College Tennis Wire

Daily NCAA Division I tennis news feed with photos, ACC teams shown first.

- Live page: https://claude.ai/artifact/NzUrsLhX8A6PZUQTxCnVwS
- `index.html` is the page source. Stories live in the artifact's database
  (`stories` collection, plus `meta/status` for the last-refreshed time).
- A scheduled routine ("College Tennis Wire daily refresh", 5:47 AM Eastern) searches
  the web each morning, adds new stories, and drops ones older than 30 days.
