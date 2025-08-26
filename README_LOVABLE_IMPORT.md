# Lovable Intake Kit v1

**Date:** 2025-08-25

This kit is organized to make importing your project into **Lovable** smooth by aligning with how Lovable syncs code from GitHub and how it handles static assets and larger files. 

## What to put where

- **GitHub repo (synced to Lovable)** → code, Markdown docs, small images/PNGs/SVGs, CSVs (keep individual files **≤25 MiB** if uploading via web; command line supports up to **100 MiB** per file).
- **GitHub Releases** → large binaries (up to **2 GiB per file**) versioned alongside the repo (e.g., demo videos, packaged zips). Link to them from docs.
- **Supabase Storage (optional)** → runtime uploads or assets your app fetches at runtime. Free tier typically supports **~50 MB per object**; higher tiers allow larger + resumable uploads.
- **External links (Drive/Dropbox)** → archival/reference materials that don't need to live in the repo or a release.

See `github/RELEASES.md` and `supabase/README_SUPABASE.md` for quick setup.
