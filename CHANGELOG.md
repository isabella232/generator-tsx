# Changelog

All notable changes to this project will be documented in this file. See
[Conventional Commits](https://conventionalcommits.org) for commit guidelines.

# [2.4.0](https://github.com/adobe/generator-tsx/compare/v2.3.0...v2.4.0) (2019-09-13)


### Features

* immutability-helper -> immer ([d339540](https://github.com/adobe/generator-tsx/commit/d339540))

# [2.3.0](https://github.com/adobe/generator-tsx/compare/v2.2.0...v2.3.0) (2019-09-12)


### Bug Fixes

* remove macOS from master workflow ([96c02f0](https://github.com/adobe/generator-tsx/commit/96c02f0))
* remove macOS from pr workflow (test) ([489259b](https://github.com/adobe/generator-tsx/commit/489259b))


### Features

* use GitHub workflows instead of Travis-CI ([0058214](https://github.com/adobe/generator-tsx/commit/0058214))

# [2.2.0](https://github.com/adobe/generator-tsx/compare/v2.1.0...v2.2.0) (2019-08-28)


### Features

* add stable polyfill + ie11 support ([25db6c0](https://github.com/adobe/generator-tsx/commit/25db6c0))

# [2.1.0](https://github.com/adobe/generator-tsx/compare/v2.0.0...v2.1.0) (2019-08-28)


### Features

* always use craco ([21756ee](https://github.com/adobe/generator-tsx/commit/21756ee))

# [2.0.0](https://github.com/adobe/generator-tsx/compare/v1.2.9...v2.0.0) (2019-08-22)


### Features

* upgrade react-intl, migrate to @reach/router ([fd6d25c](https://github.com/adobe/generator-tsx/commit/fd6d25c))


### BREAKING CHANGES

* The next React Router API, on the surface, looks more
like @reach/router than React Router. The migration to the @reach/router
API prepares us for this change. See the following articles:
- https://reacttraining.com/blog/reach-react-router-future/
- https://github.com/formatjs/react-intl/blob/master/docs/Upgrade-Guide.md

## [1.2.9](https://github.com/adobe/generator-tsx/compare/v1.2.8...v1.2.9) (2019-08-20)


### Bug Fixes

* ts import resolution, remove relay line from non-relay install ([1c74810](https://github.com/adobe/generator-tsx/commit/1c74810))

## [1.2.8](https://github.com/adobe/generator-tsx/compare/v1.2.7...v1.2.8) (2019-08-19)


### Bug Fixes

* use carat versions for dependencies ([7e05341](https://github.com/adobe/generator-tsx/commit/7e05341))

## [1.2.7](https://github.com/adobe/generator-tsx/compare/v1.2.6...v1.2.7) (2019-08-16)


### Bug Fixes

* add .env file for PUBLIC_URL=/ ([243e808](https://github.com/adobe/generator-tsx/commit/243e808))

## [1.2.6](https://github.com/adobe/generator-tsx/compare/v1.2.5...v1.2.6) (2019-08-16)


### Bug Fixes

* ts-helpers -> tslib, improve paths ([52f39ad](https://github.com/adobe/generator-tsx/commit/52f39ad))

## [1.2.5](https://github.com/adobe/generator-tsx/compare/v1.2.4...v1.2.5) (2019-08-16)


### Bug Fixes

* resolve tilde template filenames ([eb7a689](https://github.com/adobe/generator-tsx/commit/eb7a689))

## [1.2.4](https://github.com/adobe/generator-tsx/compare/v1.2.3...v1.2.4) (2019-08-15)


### Bug Fixes

* filter version to undefined if not provided ([f429528](https://github.com/adobe/generator-tsx/commit/f429528))
* provide default version to semver.clean ([74091e5](https://github.com/adobe/generator-tsx/commit/74091e5))

## [1.2.3](https://github.com/adobe/generator-tsx/compare/v1.2.2...v1.2.3) (2019-08-15)


### Bug Fixes

* no audit fix, postinstall only for relay ([0461e3a](https://github.com/adobe/generator-tsx/commit/0461e3a))

## [1.2.2](https://github.com/adobe/generator-tsx/compare/v1.2.1...v1.2.2) (2019-08-15)


### Bug Fixes

* remove @types/redux-mock-store ([bd846ff](https://github.com/adobe/generator-tsx/commit/bd846ff))

## [1.2.1](https://github.com/adobe/generator-tsx/compare/v1.2.0...v1.2.1) (2019-08-15)


### Bug Fixes

* use options + answers in configuring step ([a2de211](https://github.com/adobe/generator-tsx/commit/a2de211))

# [1.2.0](https://github.com/adobe/generator-tsx/compare/v1.1.3...v1.2.0) (2019-08-13)


### Features

* pick n' choose features ([4a386a4](https://github.com/adobe/generator-tsx/commit/4a386a4))

## [1.1.3](https://github.com/adobe/generator-tsx/compare/v1.1.2...v1.1.3) (2019-08-01)


### Bug Fixes

* update dependencies and inquirer implementation ([a8f8ff8](https://github.com/adobe/generator-tsx/commit/a8f8ff8)), closes [#50](https://github.com/adobe/generator-tsx/issues/50)

## [1.1.2](https://github.com/adobe/generator-tsx/compare/v1.1.1...v1.1.2) (2019-07-19)


### Bug Fixes

* **package:** update @queso/camel-case to version 0.2.0 ([55279ed](https://github.com/adobe/generator-tsx/commit/55279ed))
* **package:** update @queso/pick to version 0.6.0 ([ee80eb2](https://github.com/adobe/generator-tsx/commit/ee80eb2))
* **package:** update @queso/snake-case to version 0.2.0 ([f343ee3](https://github.com/adobe/generator-tsx/commit/f343ee3))

## [1.1.1](https://github.com/adobe/generator-tsx/compare/v1.1.0...v1.1.1) (2019-07-17)


### Bug Fixes

* version bump, fix coverage report ([0ceb67f](https://github.com/adobe/generator-tsx/commit/0ceb67f))

## [1.0.2](https://github.com/adobe/generator-tsx/compare/v1.0.1...v1.0.2) (2019-07-16)


### Bug Fixes

* remove server tsconfig dependency on @jedmao/tsconfig ([3c9aa6c](https://github.com/adobe/generator-tsx/commit/3c9aa6c))

## [1.0.1](https://github.com/adobe/generator-tsx/compare/v1.0.0...v1.0.1) (2019-07-16)


### Bug Fixes

* npm install --package-lock-only before audit fix ([0c5b8f1](https://github.com/adobe/generator-tsx/commit/0c5b8f1))

# [1.0.0](https://github.com/adobe/generator-tsx/compare/v0.4.0...v1.0.0) (2019-07-16)


### Bug Fixes

* remove translations sub-generator ([ad984a8](https://github.com/adobe/generator-tsx/commit/ad984a8))


### BREAKING CHANGES

* translations sub-generator is no longer supported

# [0.4.0](https://github.com/adobe/generator-tsx/compare/v0.3.2...v0.4.0) (2019-07-16)


### Features

* npm audit fix after installations ([5eed0e3](https://github.com/adobe/generator-tsx/commit/5eed0e3))

## [0.3.2](https://github.com/adobe/generator-tsx/compare/v0.3.1...v0.3.2) (2019-07-16)


### Bug Fixes

* add missing Nav export ([e362738](https://github.com/adobe/generator-tsx/commit/e362738))

## [0.3.1](https://github.com/adobe/generator-tsx/compare/v0.3.0...v0.3.1) (2019-07-16)


### Bug Fixes

* rename renderWithRedux.ts -> .tsx ([b13cfd8](https://github.com/adobe/generator-tsx/commit/b13cfd8))

# [0.3.0](https://github.com/adobe/generator-tsx/compare/v0.2.4...v0.3.0) (2019-07-15)


### Features

* ssr, theme context, persist theme, locale switching ([0dc2d87](https://github.com/adobe/generator-tsx/commit/0dc2d87)), closes [#15](https://github.com/adobe/generator-tsx/issues/15)

## [0.2.4](https://github.com/adobe/generator-tsx/compare/v0.2.3...v0.2.4) (2019-06-11)


### Bug Fixes

* version bump changelog ([49b2328](https://github.com/adobe/generator-tsx/commit/49b2328))

## [0.2.3](https://github.com/adobe/generator-tsx/compare/v0.2.2...v0.2.3) (2019-06-11)

### Bug Fixes

- version bump (test changelog)
  ([613ca90](https://github.com/adobe/generator-tsx/commit/613ca90))

## [0.2.2](https://github.com/adobe/generator-tsx/compare/v0.2.1...v0.2.2) (2019-06-11)

### Bug Fixes

- remove extraneous graphql-tag dependency
  ([83d6ec1](https://github.com/adobe/generator-tsx/commit/83d6ec1))

## [0.2.1](https://github.com/adobe/generator-tsx/compare/v0.2.0...v0.2.1) (2019-06-11)

### Bug Fixes

- create reducer for actions (fetch/set)
  ([f92c442](https://github.com/adobe/generator-tsx/commit/f92c442))

# [0.2.0](https://github.com/adobe/generator-tsx/compare/v0.1.6...v0.2.0) (2019-06-07)

### Features

- introduce data fetching via Relay / GraphQL
  ([ad292b1](https://github.com/adobe/generator-tsx/commit/ad292b1)), closes
  [#13](https://github.com/adobe/generator-tsx/issues/13)

## [0.1.6](https://github.com/adobe/generator-tsx/compare/v0.1.5...v0.1.6) (2019-06-01)

**Note:** Version bump only for package generator-tsx

## [0.1.5](https://github.com/adobe/generator-tsx/compare/v0.1.4...v0.1.5) (2019-05-31)

**Note:** Version bump only for package generator-tsx

## [0.1.4](https://github.com/adobe/generator-tsx/compare/v0.1.3...v0.1.4) (2019-05-30)

### Bug Fixes

- ensure .gitignore file is not ignored itself
  ([694111a](https://github.com/adobe/generator-tsx/commit/694111a))

## [0.1.3](https://github.com/adobe/generator-tsx/compare/v0.1.2...v0.1.3) (2019-05-30)

### Bug Fixes

- unignore files for npm publish
  ([baa72e5](https://github.com/adobe/generator-tsx/commit/baa72e5))

## [0.1.2](https://github.com/adobe/generator-tsx/compare/v0.1.1...v0.1.2) (2019-05-30)

**Note:** Version bump only for package generator-tsx

## [0.1.1](https://github.com/adobe/generator-tsx/compare/v0.1.0...v0.1.1) (2019-05-29)

**Note:** Version bump only for package generator-tsx

## [0.1.0](https://github.com/adobe/generator-tsx/compare/v0.0.1...v0.1.0) (2019-05-29)

### Bug Fixes

- some files should not have been ignored
  ([4e12263](https://github.com/adobe/generator-tsx/commit/4e12263))

### Features

- introduce CSS in JS via Linaria
  ([637e3d6](https://github.com/adobe/generator-tsx/commit/637e3d6)), closes
  [#14](https://github.com/adobe/generator-tsx/issues/14)

## 0.0.1 (2019-05-22)

Initial release.
