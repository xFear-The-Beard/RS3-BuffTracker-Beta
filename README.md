# RS3 BuffTracker - Beta

Beta test builds of the RS3 BuffTracker Alt1 plugin. This repo exists so I can push unreleased builds to a working Alt1 URL for testing, without shipping them to the stable release.

![Status](https://img.shields.io/badge/status-beta-red)

## Warning

This is a pre-release build. Do not use it in live combat. It may contain:

- Incomplete or partially-wired features
- Known rendering or detection regressions
- Experimental UI and controls that can change between builds
- Unstable overlay behavior

If you are here for a working combat tracker, use the stable release instead:
https://github.com/xFear-The-Beard/RS3-BuffTracker-Alt1

## What this build is for

- Verifying fixes before they ship to the stable repo
- Trying out in-progress features (currently: Style G custom overlay)
- Reproducing bugs against a known build without juggling local zips

Builds pushed here are not guaranteed to be functional end-to-end. Expect rough edges.

## Installation

Paste this link into Alt1's browser:

```
alt1://addapp/https://xfear-the-beard.github.io/RS3-BuffTracker-Beta/appconfig.json
```

You can run both the stable and beta side by side in Alt1. They register as separate apps with distinct config URLs, so installing the beta will not overwrite the stable app.

## Reporting issues

Use the stable repo's Issues and Discussions pages for anything you find:
https://github.com/xFear-The-Beard/RS3-BuffTracker-Alt1/issues
https://github.com/xFear-The-Beard/RS3-BuffTracker-Alt1/discussions

When filing a bug against a beta build, mention that you hit it in the beta repo so I can distinguish beta-only regressions from issues present in the stable release.

## Disclaimer

Unofficial third-party tool. Reads screen pixels only. No game memory access, no automation, no client modification. Use at your own discretion.

## License

MIT
