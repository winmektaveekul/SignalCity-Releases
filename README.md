# SignalCity Releases

Binary distribution repository for **SignalCity**. The Unity project and its source code are private and are not stored here.

This repository distributes **development previews**, not stable or final versions. Available public downloads are marked as prereleases. Draft releases are not anonymous downloads. No stable final release has been published.

## Windows

Obtain **SignalCityLauncherSetup** from an available preview on the [Releases page](https://github.com/winmektaveekul/SignalCity-Releases/releases). This small per-user installer does **not** bundle the game. Open the launcher, choose a game folder, click **Install Game**, then **Play**. Downloads need no GitHub account or token. Installed games play offline.

The launcher supports manual update checks, cancellation/resume, SHA-256 verification, repair and separate version folders. Close the game before updating. Previous game versions are retained for recovery and use extra disk space. Uninstalling the launcher preserves downloaded games and player saves.

Windows 10/11 x64 with .NET Framework 4.8 and Direct3D 11/12. These development previews are unsigned. Never bypass security warnings for an untrusted download.

## Release tags

- `launcher-v…`: small launcher installer, launcher metadata and checksums.
- `game-v…`: one complete game ZIP, `game-manifest.json` and checksums.
- `web-v…`: original Unity browser-demo assets, `web-assets.json` and checksums. The playable site is hosted on Cloudflare Pages; these files are not a standalone HTML recreation.

## Saves

Windows saves remain at `%USERPROFILE%\AppData\LocalLow\Signal City Lab\Signal City\SignalCity\Saves`. Installation, updates, repair and launcher uninstall do not delete them. Back up important saves before updating.

Browser saves use browser-local storage. Use **Export Save** before clearing browser data or moving hosts. Supported demo city JSON files can be imported into Windows. Story campaigns are not part of the demo. There are no cloud saves or required accounts.

## Preview limitations

The Windows preview includes the current Government/country simulation, construction, transport, companies, Enter City and twelve-chapter Story campaign. It is **not** a fully accepted stable release. Known country traffic-recovery and manufacturer-solvency acceptance failures remain. Native input and final cinematic/environmental validation remain incomplete. Some interiors are sparse. See the game release notes for details.

This repository being public does not make the game open-source. Third-party asset credits and license records are included with the game and website.
