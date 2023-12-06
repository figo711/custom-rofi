```
sudo apt-get install rofi
```
```
git clone https://github.com/figo711/custom-rofi.git
```
```
cd custom-rofi
chmod +x setup.sh
```
```
./setup.sh
```

## Launchers

**`Style` :** `~/.config/rofi/launchers/type-X/launcher.sh`
```
theme='style-1'
```

**`Colors` :** `~/.config/rofi/launchers/type-X/shared/colors.rasi`
```css
@import "~/.config/rofi/colors/onedark.rasi"
```

## Applets

|Applets|Description|Required Applications|
|:-|:-|:-|
|**`MPD`**|Control the song play through **`mpd`**|`mpd`, `mpc`|
|**`Screenshot`**|Take screenshots using **`maim`**|`maim`, `xrandr`, `dunst`, `xclip`|
|**`Volume`**|Display and control volume with dynamic icons and mute status|`amixer` and `pavucontrol`|

> To use your programs with these applets, Edit the scripts in `~/.config/rofi/applets/bin` directory.

**`Theme` :** `~/.config/rofi/applets/shared/theme.bash`
```ini
type="$HOME/.config/rofi/applets/type-1"
style='style-1.rasi'
```

**`Colors` :** `~/.config/rofi/applets/shared/colors.rasi`
```css
@import "~/.config/rofi/colors/onedark.rasi"
```

## Powermenus

**`Style` :** `~/.config/rofi/powermenu/type-X/powermenu.sh`
```
theme='style-1'
```

**`Colors` :** `~/.config/rofi/powermenu/type-X/shared/colors.rasi`
```css
@import "~/.config/rofi/colors/onedark.rasi"
```
