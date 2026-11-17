# Fatawa Razviya — Jild 8 tashreeh merge

Merges the 13 Jild 8 easy-Urdu tashreeh chunk files (`jild-08-chunk-01.json`
… `jild-08-chunk-13.json`) into one file, `jild-08.json` (367 items, 619
pages, volume_id 48), using `merge_jild8.py`.

The merge runs on GitHub Actions (`.github/workflows/merge.yml`) because
the local VM currently blocks file writes from exec sessions. The workflow
verifies the merged file (367 items, 619 unique pages, unique ids, no empty
`tashreeh_jawab`) and publishes `jild-08.json` as a release asset on tag
`v1.0`.
