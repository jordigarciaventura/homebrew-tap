# Homebrew Tap

Personal [Homebrew](https://brew.sh) tap for formulae and casks by [@jordigarciaventura](https://github.com/jordigarciaventura).

## Installation

Add the tap:

```sh
brew tap jordigarciaventura/tap
```

Then install a package:

```sh
brew install <formula>
brew install --cask <cask>
```

Or install directly without tapping first:

```sh
brew install jordigarciaventura/tap/<formula>
```

## Available packages

### Formulae

| Name | Description |
| ---- | ----------- |
| _none yet_ | |

### Casks

| Name | Description |
| ---- | ----------- |
| _none yet_ | |

## Updating

```sh
brew update
brew upgrade <formula>
```

## Uninstalling

```sh
brew uninstall <formula>
brew untap jordigarciaventura/tap
```

## Repository layout

```
Formula/   # Homebrew formulae (*.rb)
Casks/     # Homebrew casks (*.rb)
```

## Documentation

- `brew help`
- `man brew`
- [Homebrew documentation](https://docs.brew.sh)
- [How to create and maintain a tap](https://docs.brew.sh/How-to-Create-and-Maintain-a-Tap)
