# zathura-color-schemes

A collection of color schemes for [zathura](https://pwmt.org/projects/zathura/), the keyboard-driven document viewer.

## Available Schemes

### Yaru

A light theme based on Ubuntu's [Yaru](https://github.com/ubuntu/yaru) design language. Uses the official Yaru palette with warm greys, Ubuntu orange accents, and high-contrast statusbar/inputbar.

| Element | Color |
|---|---|
| Background | `#D5CFCA` |
| Foreground | `#2C001E` |
| Accent (highlight, index) | `#E95420` (Ubuntu orange) |
| Warning | `#F99B15` |
| Info | `#19B6EE` |

## Installation

Copy the desired scheme into your zathura config directory:

```sh
cp yaru/zathurarc ~/.config/zathura/zathurarc
```

Or source it from your existing config:

```sh
include /path/to/zathura-color-schemes/yaru/zathurarc
```

## License

[MIT](LICENSE)
