# Business Partner B2+ — lesson templates

Master templates for Business Partner B2+ (all lessons, all versions).

- `index.html` — Contents: all units and lessons, track switch (For everyone / IT / PM / Design), progress
- `lessons/<lesson>/<track>/` — `lesson.html`, `hw.html` (answers sync to Supabase), `extra.html`
- Tracks: `all`, `it`, `pm`, `design` (a lesson may have only `all`)
- Contents is generated from `bp-a2plus/tools`: `python3 build_contents.py OUT.html cfg_b2plus`

Student repos copy lessons from here.
