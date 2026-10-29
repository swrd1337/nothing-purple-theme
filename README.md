# Nothing Purple

A purple-accented variant of [Nothing by jomada](https://gitlab.com/jomada/nothing)
for KDE Plasma, using **`#a277ff`**.

Includes purple desktop accents, taskbar hover highlights, panel glow, and window
close buttons. Window corners are square and the close button uses a flat fill
without a gradient or ring. Warning/error colors are retained.

## Contents

- `plasma/desktoptheme/NothingPurple/` — Plasma desktop theme
- `aurorae/themes/NothingPurple/` — Aurorae window decoration
- `color-schemes/NothingPurple.colors` — application color scheme
- `konsole/NothingPurple.colorscheme` — matching Konsole colors, 78% opacity and blur

The original Nothing theme is not overwritten. This is not a complete global
theme package: wallpapers, icons, and cursors are not bundled.

## Install

Run from this directory:

```sh
mkdir -p ~/.local/share/plasma/desktoptheme ~/.local/share/aurorae/themes ~/.local/share/color-schemes
cp -R plasma/desktoptheme/NothingPurple ~/.local/share/plasma/desktoptheme/
cp -R aurorae/themes/NothingPurple ~/.local/share/aurorae/themes/
cp color-schemes/NothingPurple.colors ~/.local/share/color-schemes/
```

In KDE System Settings, select **Nothing Purple** for Plasma Style, Window
Decorations, and Colors. Set the custom accent color to **`#a277ff`** if desired.

On Plasma 6, the desktop style can also be selected with:

```sh
plasma-apply-desktoptheme NothingPurple
```

### Konsole (optional)

```sh
mkdir -p ~/.local/share/konsole
cp konsole/NothingPurple.colorscheme ~/.local/share/konsole/
```

Edit your Konsole profile and select **Nothing Purple** under Appearance. This
uses the theme's charcoal background and purple accents, with 78% opacity and
background blur. KDE's Blur desktop effect must be enabled.

## Credits and licensing

Original theme and artwork by **jomada**. This variant changes accent colors and
theme identifiers. Original attribution and license declarations remain in the
theme metadata; no new license is assigned to the original artwork here.
