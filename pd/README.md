# pd-owned files

`upstream-tag` records the upstream release the last sync merged.
The sync compares it with the latest upstream release tag and does
nothing when they agree, so an ordinary day costs one tag lookup.
