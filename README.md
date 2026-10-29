<p align="center"><img width="128px" height="128px" src="https://resources.jetbrains.com/storage/products/company/brand/logos/PhpStorm_icon.png" alt="PhpStorm logo."></p>
<h2 align="center">PhpStorm AppImage</h2>
<h3 align="center">Unofficial / Community provided PhpStorm AppImage</h3>

[![PhpStorm AppImage release](https://github.com/valicm/PhpStorm-AppImage/actions/workflows/release.yml/badge.svg?branch=main)](https://github.com/valicm/PhpStorm-AppImage/actions/workflows/release.yml)

## Get Started

#### [Download the latest release](https://github.com/valicm/PhpStorm-AppImage/releases/latest)
- stable release only
- supports update of the AppImage

### Executing
#### File Manager
Double-click the `*.AppImage` file and you are done!

> In normal cases, the above method should work, but in some cases you 
> need mark file as executable. You can do this using File manager -> right click > Properties > Allow Execution,
> or by terminal issuing command `chmod +x PhpStorm-*.AppImage`

#### AppImageLauncher
Use AppImageLauncher for better desktop integration ==> [download AppImageLauncher](https://github.com/TheAssassin/AppImageLauncher)

#### Terminal
```bash
chmod +x PhpStorm-*.AppImage
./PhpStorm-*.AppImage
```

#### Build
The AppImage is built from .tar.gz PhpStorm package by GitHub Continuous Integration 
with the [Go AppImage packager v2.0.0](https://github.com/valicm/appimage-bash/tree/v2.0.0).

Desktop entry values are defined inline in `.github/workflows/release.yml`; no separate desktop file is required. Builds update `latest`, publish versioned releases, and retain the newest 10 managed versioned releases.

____________________________________________________________________________________________________________________________________
_PhpStorm and the PhpStorm logo are registered trademarks of JetBrains s.r.o._
