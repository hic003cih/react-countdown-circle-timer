# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

## [2.5.1](https://github.com/vydimitrov/react-countdown-circle-timer/compare/v2.5.0...v2.5.1) (2021-03-25)


### Bug Fixes

* **mobile:** react-native ignore pattern in tests ([16cf3cc](https://github.com/vydimitrov/react-countdown-circle-timer/commit/16cf3ccab416d258ce50d6e1bfb8fdbad9bc31a0))





# [2.5.0](https://github.com/vydimitrov/react-countdown-circle-timer/compare/v2.4.0...v2.5.0) (2021-02-15)


### Bug Fixes

* change from or to null operator and other fixes suggested in PR. ([2e79ed3](https://github.com/vydimitrov/react-countdown-circle-timer/commit/2e79ed3480bb723715bd287ad4e4b001a87254d4))
* the issue of stroke overflowing when trailStrokeWidth is different from strokeWidth ([b3d3aab](https://github.com/vydimitrov/react-countdown-circle-timer/commit/b3d3aab1d175bc95478efa7f0ebf3c3d50a66c37))


### Features

* Add inner and outer stroke width prop to timer. ([bdc35a7](https://github.com/vydimitrov/react-countdown-circle-timer/commit/bdc35a7c7ec449d452babbb8f1610e7588bca6e3))
* add snapshots for trailStrokeWidth for web also ([ce12b54](https://github.com/vydimitrov/react-countdown-circle-timer/commit/ce12b5419a6810fbfe83bce4aa04dbd1630f04f8))
* add test for trailStrokeWidth mobile ([67542b1](https://github.com/vydimitrov/react-countdown-circle-timer/commit/67542b171ad2cb041bf52d470af8142ec1d3ba3a))





# [2.4.0](https://github.com/vydimitrov/react-countdown-circle-timer/compare/v2.3.12...v2.4.0) (2021-01-15)


### Bug Fixes

* **web:** put the browser list to the correct file ([2e4d510](https://github.com/vydimitrov/react-countdown-circle-timer/commit/2e4d510fefbd1dfce7ae2a0f58c6809268aa9f20))


### Features

* **web:** add browser list to package.json ([a88c8c8](https://github.com/vydimitrov/react-countdown-circle-timer/commit/a88c8c8a89a4a794265d333c672be02c5409bc8c))





## [2.3.12](https://github.com/vydimitrov/react-countdown-circle-timer/compare/v2.3.11...v2.3.12) (2021-01-14)


### Bug Fixes

* **web:** support for IE11 ([201f996](https://github.com/vydimitrov/react-countdown-circle-timer/commit/201f996c478d961a02d90997bd4e3ef8a9ef8434))





## [2.3.11](https://github.com/vydimitrov/react-countdown-circle-timer/compare/v2.3.10...v2.3.11) (2021-01-10)

**Note:** Version bump only for package countdown-circle-timer-monorepo





## [2.3.10](https://github.com/vydimitrov/react-countdown-circle-timer/compare/v2.3.9...v2.3.10) (2020-10-11)


### Bug Fixes

* **mobile:** wrong onComplete type fixes[#56](https://github.com/vydimitrov/react-countdown-circle-timer/issues/56) ([07b2a6c](https://github.com/vydimitrov/react-countdown-circle-timer/commit/07b2a6c3689a154b84f0b248ff231433d4db9912))





## [2.3.9](https://github.com/vydimitrov/react-countdown-circle-timer/compare/v2.3.8...v2.3.9) (2020-09-06)


### Bug Fixes

* **mobile:** prevent running onComplete while in finished state fixes [#51](https://github.com/vydimitrov/react-countdown-circle-timer/issues/51) ([0ea726d](https://github.com/vydimitrov/react-countdown-circle-timer/commit/0ea726da6d91cb197a41ebb0034702ea799dc8e8))





## [2.3.8](https://github.com/vydimitrov/react-countdown-circle-timer/compare/v2.3.7...v2.3.8) (2020-08-29)


### Bug Fixes

* **mobile:** add correct dependencies in hooks ([9d77921](https://github.com/vydimitrov/react-countdown-circle-timer/commit/9d779212419c2e7ad397cffab7a3c1aef759534f))
* minutes formatting in recipes on Readme page ([acab4c8](https://github.com/vydimitrov/react-countdown-circle-timer/commit/acab4c85fb9106a54d0b698e45af28e2db7709eb))


### Features

* add eslint plugin:react-hooks ([288320f](https://github.com/vydimitrov/react-countdown-circle-timer/commit/288320f9d2bfca4e5f20d528221214dd06ff9f52))





## 2.3.7 (2020-07-24)

**Note:** Configure Github action to release using Lerna. No changes on component code.

## 2.3.6 (2020-07-22)

**Note:** Configure Github action to release using Lerna. No changes on component code.

## 2.3.5 (2020-07-22)

**Note:** Configure Github action to release using Lerna. No changes on component code.

## 2.3.4 (2020-07-22)

**Note:** Configure Github action to release using Lerna. No changes on component code.

## [2.3.3](https://github.com/vydimitrov/react-countdown-circle-timer/compare/v2.3.2...v2.3.3) (2020-07-21)

**Note:** An attempt to configure Lerna to create Github releases. No changes on component code.

## [2.3.2](https://github.com/vydimitrov/react-countdown-circle-timer/compare/v2.3.1...v2.3.2) (2020-07-21)

**Note:** An attempt to configure Lerna to create Github releases. No changes on component code.

## [2.3.1](https://github.com/vydimitrov/react-countdown-circle-timer/compare/v2.3.0...v2.3.1) (2020-07-21)

**Note:** An attempt to configure Lerna to create Github releases. No changes on component code.

# 2.3.0 (2020-07-21)

### Features

- **web, mobile:** allow passing string as a single color to colors prop ([f5ba08c](https://github.com/vydimitrov/react-countdown-circle-timer/commit/f5ba08c604f89fcf42bf4dbb62f883bd7b2d1647))

## 2.0.0

**Implemented enhancements:**

- Make the repo monorepo handled by Lerna
- Breaking changes:
  - Remove the old `startAt` prop. The recommended prop to use is `initialRemainingTime` instead.
  - Remove `margin` styles from the wrapper and all svg styles
  - `durationSeconds` is renamed to just `duration`. The duration is still in **seconds**
  - `renderTime` prop is now deprecated. React `children` should be used instead. The `children` prop accepts a render function or a component where `remainingTime` and `elapsedTime` are passed as props.
  - `renderAriaTime` prop will receive as an argument an object with the `remainingTime` and `elapsedTime`

## 1.2.1 (April 8th, 2020)

**Implemented enhancements:**

- Refactor internal logic to prep the code for monorepo
- Remove `path.getTotalLength()` dependency and add logic to calculate the path length
- Improve test coverage
- Add Prettier

**Bug fixes:**

- Fix an issue in Firefox where the progress bar does not get to 0

## 1.1.1 (February 23th, 2020)

**Implemented enhancements:**

- Add GitHub workflow to report test coverage and build status
- Add a new badge for weekly downloads

## 1.1.0 (February 1st, 2020)

**Implemented enhancements:**

- Replace `startAt` with `initialRemainingTime`. Using `startAt` in the context of countdown is confusing
- `startAt` can be used until the next major release for backward compatibility
- `initialRemainingTime` sets the initial remaining time when the countdown starts

## 1.0.6 (January 12th, 2020)

**Implemented enhancements:**

- Add TypeScript type definitions

## 1.0.5 (December 22nd, 2019)

**Implemented enhancements:**

- Add test coverage

## 1.0.4 (December 3rd, 2019)

**Implemented enhancements:**

- Add `a11y` support by exposing two additional props `ariaLabel` and `renderAriaTime`

## 1.0.3 (November 16th, 2019)

**Implemented enhancements:**

- Replace custom hook that handles animation loop with [useElapsedTime ](https://github.com/vydimitrov/use-elapsed-time)
- Add Changelog file
