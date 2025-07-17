# Wchmb Subsurface

## Why?
Apple Silicon is only supported by Qt6. Currently Subsurfaces is on version 6.0.x and it still uses Qt5.

As I said [here](https://github.com/Homebrew/homebrew-cask/pull/219984#issuecomment-3083437589), I took this release (5.0.10-qt6-universal) because even though it dates back from 2022, it's the latest build with Qt6.

Subsurface's team will eventually release a Qt6 build based on v6, which won't require Rosetta. But as you can see it's taking a lot of efforts and time.

Until that day comes, here's my little workaround.

## How do I install these formulae?

`brew install wchmb/subsurface/<formula>`

Or `brew tap wchmb/subsurface` and then `brew install <formula>`.

Or, in a `brew bundle` `Brewfile`:

```ruby
tap "wchmb/subsurface"
brew "<formula>"
```

## Documentation

`brew help`, `man brew` or check [Homebrew's documentation](https://docs.brew.sh).
