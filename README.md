# "Unofficial" Init7 Chrome Rot Theme

[![Chrome Screenshot](chromium-screenshot.png)](https://chrome.google.com/webstore/search/Init7)

## User Installation
1. [Search for "Init7" on the Chrome Web Store](https://chrome.google.com/webstore/search/Init7)

## Developer Installation
1. Git clone this project
1. In a Chromium based browser, open **Settings**
1. Go to **Extensions**
1. Switch on **Developer mode**
1. **Load unpacked** and open this git repo clone

## Developer Help
- [Developer: Chrome Themes](https://developer.chrome.com/apps/themes)
- [Chrome Theme Reference](https://docs.google.com/Doc?docid=0Aa86IE02TBXPZGtzZDU0NV85ZnFocnQzZGo)

### Definitions
- `ntp` = "New Tab Page"
- `inactive` = When the browser is not the active app (but you can see the window in the background)

###  Theme Colors
| Name | HEX | RGB |
|---|---|---|
| Rot | #EB5A6D | [235, 90, 109] |
| White | #FFF | [255, 255, 255] |
| Black | #000 | [255, 255, 255] |

### Tints Help
> Tints are in Hue-Saturation-Lightness (HSL) format, using floating-point numbers in the range `0 - 1.0`:

- **Hue** is an absolute value, with `0` and `1` being red.
- **Saturation** is relative to the currently provided image. `0.5` is no change, `0` is totally desaturated, and `1` is full saturation.
- **Lightness** is also relative, with `0.5` being no change, `0` as all pixels black, and `1` as all pixels white.

> You can alternatively use `-1.0` for any of the HSL values to specify no change.

## NOTE
- This theme has not been endorsed or approved by [Init7](https://www.init7.net/) - and as such they can't support it. [Raise an Issue](https://github.com/mountainash/Init7-WebBrowser-Theme/issues) if you have any problems or suggestions.

## TODO:
- [ ] Do a DE (German) localisation (open to contributions)
- [ ] [Firefox Theme](https://developer.mozilla.org/en-US/docs/Mozilla/Add-ons/WebExtensions/manifest.json/theme)
- [ ] Hope that Chromium implements an inactive setting for bookmark text (eg. `colors.bookmark_text_inactive` or `tints.buttons_inactive`)
- [ ] Hope that Chromium implements a background image size setting (eg. `properties.ntp_background_size`)