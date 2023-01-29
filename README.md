# renovate-config

![ci](https://github.com/yikoyu/renovate-config/actions/workflows/test.yml/badge.svg?branch=master)

Personal preset for [Renovate](https://github.com/singapore/renovate).

## Usage

Add this into `renovate.json`:

```json
{
  "extends": ["github>yikoyu/renovate-config:PRESET"]
}
```

## Presets
### default
It contains only language independent defaults that we want to apply to **all** repositories.

It is the only preset that doesn't need to be named when using it:

```json
{
  "extends": ["github>yikoyu/renovate-config"]
}
```

### javascript

Adds some rules we generally apply in javascript related repositories.  
```json
{
  "extends": ["github>yikoyu/renovate-config:javascript"]
}
```

### python

Adds some rules we generally apply in python related repositories.
```json
{
  "extends": ["github>yikoyu/renovate-config:python"]
}
```

## Useful Links

- [Configuration Options](https://renovatebot.com/docs/configuration-options)
- [Renovate Presets](https://docs.renovatebot.com/config-presets/)

## License

MIT
