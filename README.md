# BeatForge mods

The catalogue BeatForge's **Browse** page reads. Install mods from inside BeatForge, which checks the catalogue's
signature and each file's hash before installing anything.

- The catalogue is the `index` release (`index.json` + `index.json.sig`); each mod version is its own release.
- Score-safe mods keep leaderboard scores on only with an up-to-date loader; BeatForge shows which.

## Submitting a mod

Submissions come from BeatForge itself, with the mod creation tools unlocked: open the mod, press **Submit…**, sign
in to GitHub, and choose whether it's a new mod or a new version of one that's here. BeatForge opens an issue in
this repo for you.

A check runs on every submission and comments on the issue. It refuses whole copies of the game's files (submit
patches instead), music packs, and audio over 1 MB. Once a submission is approved it is published and shows up in
Browse.

Issues that aren't submissions are welcome too: a mod that misbehaves, or one that shouldn't be here.
