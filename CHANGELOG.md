### [7.0.1](https://github.com/ipfs/js-datastore-core/compare/v7.0.0...v7.0.1) (2022-01-28)


### Bug Fixes

* fix generated types to missing import ([#86](https://github.com/ipfs/js-datastore-core/issues/86)) ([8805e71](https://github.com/ipfs/js-datastore-core/commit/8805e71f5840dac2dea4d3220b4f3975b39d5161)), closes [#85](https://github.com/ipfs/js-datastore-core/issues/85)

## [7.0.0](https://github.com/ipfs/js-datastore-core/compare/v6.0.7...v7.0.0) (2022-01-19)


### ⚠ BREAKING CHANGES

* key prefixes are no longer stripped by MountDatastore

### Bug Fixes

* do not strip prefixes for MountDatastores ([#82](https://github.com/ipfs/js-datastore-core/issues/82)) ([73bae74](https://github.com/ipfs/js-datastore-core/commit/73bae74ac794bf7585d432a3337e40fe85cb68f4))


### Trivial Changes

* switch to unified ci ([#83](https://github.com/ipfs/js-datastore-core/issues/83)) ([b3f79e6](https://github.com/ipfs/js-datastore-core/commit/b3f79e6d07440e37aabc83d1ebabe2b5c0e2bd30))

## [6.0.7](https://github.com/ipfs/js-datastore-core/compare/v6.0.6...v6.0.7) (2021-09-09)



## [6.0.6](https://github.com/ipfs/js-datastore-core/compare/v6.0.5...v6.0.6) (2021-09-09)



## [6.0.5](https://github.com/ipfs/js-datastore-core/compare/v6.0.4...v6.0.5) (2021-09-08)



## [6.0.4](https://github.com/ipfs/js-datastore-core/compare/v6.0.3...v6.0.4) (2021-09-08)



## [6.0.3](https://github.com/ipfs/js-datastore-core/compare/v6.0.2...v6.0.3) (2021-09-08)



## [6.0.2](https://github.com/ipfs/js-datastore-core/compare/v6.0.1...v6.0.2) (2021-09-08)



## [6.0.1](https://github.com/ipfs/js-datastore-core/compare/v6.0.0...v6.0.1) (2021-09-08)



# [6.0.0](https://github.com/ipfs/js-datastore-core/compare/v5.0.2...v6.0.0) (2021-09-08)


### chore

* update to esm ([#71](https://github.com/ipfs/js-datastore-core/issues/71)) ([ace9a06](https://github.com/ipfs/js-datastore-core/commit/ace9a06e879ff3fef9493754a7bbc7981595d9a4))


### BREAKING CHANGES

* deep requires/imports are no longer possible



## [5.0.2](https://github.com/ipfs/js-datastore-core/compare/v5.0.1...v5.0.2) (2021-08-23)



## [5.0.1](https://github.com/ipfs/js-datastore-core/compare/v5.0.0...v5.0.1) (2021-07-23)


### Bug Fixes

* use streaming methods where possible ([#65](https://github.com/ipfs/js-datastore-core/issues/65)) ([ec90398](https://github.com/ipfs/js-datastore-core/commit/ec9039827829dcd0e6e5c652ecb8707e80c48010))



# [5.0.0](https://github.com/ipfs/js-datastore-core/compare/v4.0.0...v5.0.0) (2021-07-06)


### chore

* update deps ([e154404](https://github.com/ipfs/js-datastore-core/commit/e154404317838f147fbb9ab11417a8d671aba9a4))


### BREAKING CHANGES

* implements new interface-datastore types, will cause duplicates in the dep tree



# [4.0.0](https://github.com/ipfs/js-datastore-core/compare/v3.0.0...v4.0.0) (2021-04-15)


### Bug Fixes

* fix async sharding tests ([#49](https://github.com/ipfs/js-datastore-core/issues/49)) ([a546afb](https://github.com/ipfs/js-datastore-core/commit/a546afb0cef751025aac73c5f3bcfa3bedd1dff4))


### Features

* split .query into .query and .queryKeys ([#59](https://github.com/ipfs/js-datastore-core/issues/59)) ([6f829db](https://github.com/ipfs/js-datastore-core/commit/6f829db2e8d1aed3b9c36a7bb95625a15c077e02))



# [3.0.0](https://github.com/ipfs/js-datastore-core/compare/v2.0.1...v3.0.0) (2021-01-22)


### Bug Fixes

* fix ShardingDatastore creation ([#48](https://github.com/ipfs/js-datastore-core/issues/48)) ([21b48e7](https://github.com/ipfs/js-datastore-core/commit/21b48e7ccc965a1422f8a0f7eadbd83715b5cac6))


### Features

* ts types, github ci and clean up ([#39](https://github.com/ipfs/js-datastore-core/issues/39)) ([bee45ae](https://github.com/ipfs/js-datastore-core/commit/bee45ae0b778171d0919e135ea8affcf2d6de635))



## [2.0.1](https://github.com/ipfs/js-datastore-core/compare/v2.0.0...v2.0.1) (2020-11-09)



<a name="2.0.0"></a>
# [2.0.0](https://github.com/ipfs/js-datastore-core/compare/v1.1.0...v2.0.0) (2020-07-29)


### Bug Fixes

* remove node buffers ([#27](https://github.com/ipfs/js-datastore-core/issues/27)) ([a9786b9](https://github.com/ipfs/js-datastore-core/commit/a9786b9))


### BREAKING CHANGES

* no longer uses node Buffers, only Uint8Arrays



<a name="1.1.0"></a>
# [1.1.0](https://github.com/ipfs/js-datastore-core/compare/v1.0.0...v1.1.0) (2020-05-07)


### Bug Fixes

* **ci:** add empty commit to fix lint checks on master ([a19da65](https://github.com/ipfs/js-datastore-core/commit/a19da65))


### Features

* add streaming/cancellable API ([#23](https://github.com/ipfs/js-datastore-core/issues/23)) ([5e7858e](https://github.com/ipfs/js-datastore-core/commit/5e7858e))



<a name="1.0.0"></a>
# [1.0.0](https://github.com/ipfs/js-datastore-core/compare/v0.7.0...v1.0.0) (2020-04-06)


### Bug Fixes

* add buffer and cleanup ([#22](https://github.com/ipfs/js-datastore-core/issues/22)) ([f0f64a9](https://github.com/ipfs/js-datastore-core/commit/f0f64a9))



<a name="0.7.0"></a>
# [0.7.0](https://github.com/ipfs/js-datastore-core/compare/v0.6.1...v0.7.0) (2019-05-29)



<a name="0.6.1"></a>
## [0.6.1](https://github.com/ipfs/js-datastore-core/compare/v0.6.0...v0.6.1) (2019-05-23)


### Bug Fixes

* remove leftpad and cleanup ([8558fcd](https://github.com/ipfs/js-datastore-core/commit/8558fcd))



<a name="0.6.0"></a>
# [0.6.0](https://github.com/ipfs/js-datastore-core/compare/v0.5.0...v0.6.0) (2018-10-24)



<a name="0.5.0"></a>
# [0.5.0](https://github.com/ipfs/js-datastore-core/compare/v0.4.0...v0.5.0) (2018-09-19)


### Bug Fixes

* **ci:** build on appveyor ([#9](https://github.com/ipfs/js-datastore-core/issues/9)) ([687314b](https://github.com/ipfs/js-datastore-core/commit/687314b))


### Features

* add basic error codes ([bf79768](https://github.com/ipfs/js-datastore-core/commit/bf79768))



<a name="0.4.0"></a>
# [0.4.0](https://github.com/ipfs/js-datastore-core/compare/v0.3.0...v0.4.0) (2017-11-04)


### Bug Fixes

* sharding and query for windows interop ([#6](https://github.com/ipfs/js-datastore-core/issues/6)) ([845316d](https://github.com/ipfs/js-datastore-core/commit/845316d))



<a name="0.3.0"></a>
# [0.3.0](https://github.com/ipfs/js-datastore-core/compare/v0.2.0...v0.3.0) (2017-07-23)



<a name="0.2.0"></a>
# [0.2.0](https://github.com/ipfs/js-datastore-core/compare/v0.1.0...v0.2.0) (2017-03-23)


### Features

* add open method ([1462fcc](https://github.com/ipfs/js-datastore-core/commit/1462fcc))



<a name="0.1.0"></a>
# 0.1.0 (2017-03-15)
