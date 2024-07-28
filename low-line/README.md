# low line

[![CC BY-SA 4.0][cc-by-sa-image]][cc-by-sa]

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/
[cc-by-sa-image]: https://licensebuttons.net/l/by-sa/4.0/88x31.png
[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg

By [scillidan](https://github.com/scillidan).


## Tools

- [png-to-ico](https://github.com/steambap/png-to-ico)

## Notes

Create `lightTheme` from `darkTheme`:

```sh
magick convert darkThemeImage.png -channel RGB -negate lightThemeImage.png
```

Convert `.png` to `.ico`:

```sh
png-to-ico Image.png > Image.ico
```