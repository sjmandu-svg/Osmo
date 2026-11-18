# Osmo

A dock for Windows 11 that takes the place of the taskbar: a floating bar with widgets for apps, media, volume, network, system load, timers, notes, wallpapers and more.

## Install

1. Download **osmo-dock.exe** from the [latest release](https://github.com/sjmandu-svg/Osmo/releases/latest).
2. Run it and answer **Yes** when it asks to install.

It installs for your Windows account only (no administrator rights), starts with Windows, and keeps itself up to date.

Windows may show a "Windows protected your PC" notice the first time, because the program is not signed with a commercial certificate. Choose **More info**, then **Run anyway**.

## Using it

- Move the pointer to the bottom edge of the screen to bring the bar up.
- Right-click the bar for **Settings**, widgets, themes, and **Start with Windows**.
- The Windows taskbar is put back whenever the dock is closed.

## Updates

An installed dock checks this page for a newer release shortly after it starts and every few hours, downloads it, verifies that it was signed by the publisher, and restarts into it. To turn this off, add `updates = off` to `%LOCALAPPDATA%\OsmoDock\config.txt`.

## Remove

**Settings > Apps > Installed apps > Osmo > Uninstall.** Your settings and notes in `%LOCALAPPDATA%\OsmoDock` are kept; delete that folder too if you want them gone.

If the taskbar is ever missing after a crash, run `osmo-dock.exe --restore`.
