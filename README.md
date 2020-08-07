# QuickLook.Plugin.ApkViewer
Android package plugin for [QuickLook](https://github.com/QL-Win/QuickLook), allowing to preview `.apk` file

## Download and Installation
1. Go to [Release page](https://github.com/canheo136/QuickLook.Plugin.ApkViewer/releases) and download the latest version.
2. Make sure that you have QuickLook running in the background. Press `Spacebar` on the downloaded `.qlplugin` file.
3. Click the `Install` button in the popup window.
4. Restart QuickLook.

## Development
1. Clone this repo
2. Clone [QuickLook.Common](https://github.com/QL-Win/QuickLook.Common)
3. Build project with Release profile.
4. Run Scripts\pack-zip.ps1.
5. Find plugin `QuickLook.Plugin.ApkViewer.qlplugin` in the project directory.

## Known problems
- Failed to load package with filename in unicode `UTF-8`. If you get a message with content **"Can not load package"**, please change your filename and try again.
- Can't extract icon from some packages. This problem depend on how the package is compressed and extract process takes too much time (~~**SlowLook**~~)

## License
 &nbsp;&nbsp;&nbsp;&nbsp;**GPL-3.0**
