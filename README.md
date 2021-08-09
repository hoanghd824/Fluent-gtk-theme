# Fluent theme

Fluent is a Fluent design theme for GNOME/GTK based desktop environments. See also [Fluent Icon theme](https://github.com/vinceliuice/Fluent-icon-theme).

### Normal version
![screenshot01](screenshot01.png?raw=true)

### Blur version (Only for Gnome-Shell desktop)
![screenshot-blur](screenshot-blur.jpg?raw=true)

- Blur version requirement [Blur Me](https://extensions.gnome.org/extension/4236/blur-me/)

## Requirements

- GTK `>=3.20`
- `gnome-themes-extra` (or `gnome-themes-standard`)
- Murrine engine — The package name depends on the distro.
  - `gtk-engine-murrine` on Arch Linux
  - `gtk-murrine-engine` on Fedora
  - `gtk2-engine-murrine` on openSUSE
  - `gtk2-engines-murrine` on Debian, Ubuntu, etc.
- `sassc` — build dependency

## Installation

### Manual Installation

Run the following commands in the terminal:

```sh
./install.sh
```

> Tip: `./install.sh` allows the following options:

```
-d, --dest DIR          Specify destination directory (Default: /usr/share/themes)
-n, --name NAME         Specify theme name (Default: Fluent)
-t, --theme VARIANT     Specify theme color variant(s) [default|purple|pink|red|orange|yellow|green|grey|all] (Default: blue)
-c, --color VARIANT     Specify color variant(s) [standard|light|dark] (Default: All variants)
-s, --size VARIANT      Specify size variant [standard|compact] (Default: All variants)
--tweaks                Specify versions for tweaks [solid|float|round|blur|noborder|square]
                        solid:    no transparency version
                        float:    floating panel
                        round:    rounded windows
                        blur:     blur version for 'Blur-Me'
                        noborder: windows and menu with no border
                        square:   square windows button
-h, --help              Show help
```

![Fluent-view](Fluent-view.png?raw=true)

> For more information, run: `./install.sh --help`

### Flatpak Installation

Automatically install your host GTK+ theme as a Flatpak.

- [pakitheme](https://github.com/refi64/pakitheme)

### Wallpaper
[Install Wallpapers](src/wallpaper)

#### Preview
![wallpaper](src/wallpaper/wallpaper-1080p/wallpaper-default-flat.png?raw=true)

### Firefox theme
[Install Firefox theme](src/firefox)

#### Preview
![preview01](src/firefox/preview01.png?raw=true)
![preview02](src/firefox/preview02.png?raw=true)

### Fix for Dash to panel

Just install the compact version

```sh
./install.sh --tweaks compact
```

## Gtk theme widgets
![screenshot02](screenshot02.png?raw=true)
