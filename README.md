# Scoop bucket

Personal [Scoop](https://scoop.sh) bucket for [part-avocado](https://github.com/part-avocado).

```
scoop bucket add part-avocado https://github.com/part-avocado/scoop
scoop install part-avocado/fftui
```

## fftui

[fftui](https://github.com/part-avocado/fftui), a terminal interface for FFmpeg. Installs FFmpeg from Scoop's main bucket too.

`.github/workflows/update-fftui.yml` points the manifest at each new fftui release, and `.github/workflows/test.yml` installs it with Scoop on Windows after every change.
