## What

Installs a fixed version of `brew` that allows installing taps as content-addressed https://raw.githubusercontent.com/ links.

I took ~April 2020 as a baseline.

## Uninstall

```bash
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/uninstall)"
sudo rm -rf 
```

