# Trackhop for Scoop

[![Tests](https://github.com/xlollx/scoop-bucket/actions/workflows/ci.yml/badge.svg)](https://github.com/xlollx/scoop-bucket/actions/workflows/ci.yml) [![Excavator](https://github.com/xlollx/scoop-bucket/actions/workflows/excavator.yml/badge.svg)](https://github.com/xlollx/scoop-bucket/actions/workflows/excavator.yml)

The [Scoop](https://scoop.sh) bucket of [Trackhop Desktop](https://github.com/xlollx/Trackhop), which
keeps your playlists in sync across Spotify, YouTube Music, Apple Music, TIDAL, Deezer, Navidrome,
Jellyfin, Plex and more. Free and open source (GPL-3.0).

```pwsh
scoop bucket add xlollx https://github.com/xlollx/scoop-bucket
scoop install xlollx/trackhop
```

Then start *Trackhop* from the Start menu, or run `trackhop`. Your data stays in
`%APPDATA%\Trackhop`, so `scoop update trackhop` and `scoop uninstall trackhop` leave it alone.

New versions of Trackhop Desktop reach this bucket by themselves within a few hours of their release.
Problems with the app itself: [Trackhop's issues](https://github.com/xlollx/Trackhop/issues).
