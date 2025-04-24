# herodevs-replacements

This repository contains HeroDevs "replacement" presets for Mend Renovate.

## Presets and content

- `github>mend/herodevs-replacements:all`: this file contains replacements for _all_ supported HeroDevs packages

## Usage

When using Renovate, add one of the above replacements preset to your config, e.g.

```json
{
  "extends": ["github>mend/herodevs-replacements:all"]
}
```

In Renovate terms, this means that all of the `packageRules` in the preset will be included in your Renovate config.
This means that Renovate will raise "replacement" Pull Requests for any applicable libraries it finds which have HeroDevs replacements available.

## Future Work

Future work will be tracked in the Issues tab of this repository.
