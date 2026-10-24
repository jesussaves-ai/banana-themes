# BananaOS Themes

Layout themes for [BananaOS](https://github.com/JorreFog/BananaLinux), the custom firmware for the Anbernic
RG DS and RG DS Plus.

Each theme is one `.json`. The format is
[docs/THEMES.md](https://github.com/JorreFog/BananaLinux/blob/main/docs/THEMES.md); a theme that names pictures,
fonts or sounds keeps them in a folder beside its `.json`, named after the theme.

| Theme | |
| --- | --- |
| [Retroism](retroism.json) | A Platinum / Win9x desktop — grey beveled windows, a taskbar, navy selections, a teal accent — matching a niri + Quickshell "Retroism" system |

## Install

Copy a theme's `.json` (and its folder, if it has one) into `banana/themes/` on the card — over file sharing, or
with the card in a computer — then pick it in **Settings ▸ Display & sound ▸ Theme**.

## Make your own

The BananaOS checkout builds two editors: an offline web one (`tools/theme-studio/`) and a desktop one
(`tools/theme-studio-desktop/`, PySide6). Both read and write this format, so a theme made here drops straight
in. Start from any theme in this repo, or from the examples that ship with BananaOS.

Fonts: BananaOS ships Pixelify Sans. A theme may name its own `.ttf` (relative to the `.json`) — keep in mind
some popular retro fonts are proprietary and can't be redistributed.