# Azeroth Explorer — developer notes

Built from **WoW Commander Alpha Project**.

## Refresh

```bash
cd "../WoW Commander Alpha Project"
python3 scripts/sync_explorer_project.py --push
```

## Git publish

Default `--push` uploads tiles in ~1 GB batches so GitHub accepts the repo.
Release zips are split into ~1 GB parts under `exports/` for GitHub Releases.

## Open locally

File → Open → `Azeroth Explorer.kml` (keep `kml/` and `tiles/` alongside it).
