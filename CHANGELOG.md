# Changelog

Versions and bullets are arranged chronologically from latest to oldest.

## [1.0.3](https://github.com/lens0021/FemiwikiSkin/compare/v1.0.2...v1.0.3) (2025-03-23)


### Bug Fixes

* 116 ([fcf8120](https://github.com/lens0021/FemiwikiSkin/commit/fcf8120dbc1718101c1f5ba2b425e4ee87394af6))
* 185 ([04c66a8](https://github.com/lens0021/FemiwikiSkin/commit/04c66a84d1f413c657dbf14b54955ed02740135b))
* 187 ([8671c1d](https://github.com/lens0021/FemiwikiSkin/commit/8671c1d1f3038bd9f150548b13850fdf99ea8049))
* 188 ([44960f3](https://github.com/lens0021/FemiwikiSkin/commit/44960f3bb3e93d734090d1aed6d808a965e5a307))
* 189 ([798b711](https://github.com/lens0021/FemiwikiSkin/commit/798b7114cec1d12bb3ddbba8fe822ee4081e592b))
* 191 ([7646289](https://github.com/lens0021/FemiwikiSkin/commit/7646289804a73728d6e5cae9d326ccfc2d38b49e))
* 198 ([25103f6](https://github.com/lens0021/FemiwikiSkin/commit/25103f690221c227f635c59719f85010199a10a5))
* 199 ([7e08d4c](https://github.com/lens0021/FemiwikiSkin/commit/7e08d4c7b66bac3feb02da7e65a5aeedb2c449d5))

## v1.4.0 (Unreleased)

- Add a new configuration variable `$wgFemiwikiAddThisId` for pubid and tool id of [AddThis](https://www.addthis.com/). If it is set, `$wgFemiwikiFacebookAppId` will be ignored.

  ```php
  // Basic usage
  $wgFemiwikiAddThisId = 'xx-xxxxxxxxxxxxxxxx';

  // If you have multiple tools, you must specify the tool id.
  $wgFemiwikiAddThisId = [
    'pub' => 'xx-xxxxxxxxxxxxxxxx',
    'tool' => 'xxxx',
  ];
  ```

## v1.3.5

- Add missing closing label tags

## v1.3.4

- Use `$wgLogos['svg']` if `$wgLogos['icon']` is not set.
- Fix broken Echo icons

## v1.3.3

- Fix the not working markAllRead button

## v1.3.2

BUG FIXES:

- Replace normalize.css with the MediaWiki bundled version.
- Fix PHP Notice: Array to string conversion.
