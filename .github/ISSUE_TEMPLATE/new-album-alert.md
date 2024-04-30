---
name: New Album Alert
about: Submit an issue for a new Taylor Swift album
title: 'NEW ALBUM ALERT: '
labels: ''
assignees: ''

---

Checklist of things that should be updated when adding a new album:

- [ ] Add lyrics to `data-raw/lyrics`
- [ ] In terminal, run `python3 data-raw/fix-chars.py` 
- [ ] Add singles and release dates to `data-raw/releases.xlsx`
- [ ] Add Spotify album code to `data-raw/taylor-lyrics.R` (~ line 250)
- [ ] Run `data-raw/taylor-lyrics.R`
- [ ] Add color palette to `R/taylor-album-palettes.R`
- [ ] Add color to existing `album_compare` palette in `R/taylor-album-palettes.R`
- [ ] Update `album_levels` in `R/taylor-album-palettes.R`
- [ ] Add palette to `taylor_col()` functionality in `R/taylor-album-palettes.R`
- [ ] Add tests for new palettes to `tests/testthat/test-ggplot2-color-scales.R`
- [ ] Create new hex logo, update favicons
- [ ] Update CSS for pkgdown theme
