## [0.9.1](https://github.com/newrelic-forks/repolinter/compare/v0.9.0...v0.9.1) (2023-02-17)


### Bug Fixes

* split build and cleanup release ([94d9fac](https://github.com/newrelic-forks/repolinter/commit/94d9facb166817637e463742435f4b9143e97684))

# [0.9.0](https://github.com/newrelic-forks/repolinter/compare/v0.8.2...v0.9.0) (2023-02-17)


### Bug Fixes

* add backwards compatibility for blacklist -> denylist switch ([002deae](https://github.com/newrelic-forks/repolinter/commit/002deaeea1284a78a083e8d62fa4cd109fb2d52f))
* add command-exists test to axioms for stability, moved from sync to async calls ([#182](https://github.com/newrelic-forks/repolinter/issues/182)) ([0da11b9](https://github.com/newrelic-forks/repolinter/commit/0da11b9781b7ecdcb9aecdbf8fc6b10a9b3a1ee2))
* add missing github-markup dependencies to dockerfile ([b5fb88a](https://github.com/newrelic-forks/repolinter/commit/b5fb88ad4c763dcb2c693a2a41b7ce3b2f183bcf))
* attempt to fix timeout on MacOS when running axioms ([05e81ad](https://github.com/newrelic-forks/repolinter/commit/05e81add651c6d0437bc71a7c4f518d4a91f7ac5))
* broken test case. ([4816a53](https://github.com/newrelic-forks/repolinter/commit/4816a53a9958fe929623f1e5f779b362438ae4b9))
* explicitly check-out the forked repo for release job ([5c7d05b](https://github.com/newrelic-forks/repolinter/commit/5c7d05ba8122cfdabb153704d197514d17f91adb))
* file-hash now accepts legacy configuration format ([d509274](https://github.com/newrelic-forks/repolinter/commit/d50927423c965054d154adb56aaf1c48db778182))
* fix axiom object with invalid axiom ([11e7048](https://github.com/newrelic-forks/repolinter/commit/11e7048e8702850877a2fd5a63f30d93ba38dcc8))
* fix broken link behavrior with files in subdirectories ([6c14db9](https://github.com/newrelic-forks/repolinter/commit/6c14db9fb7348fd42b72bc4ffc4ef7e4d6376409))
* fix flaky glob behavior with broken symlinks ([57c0dfd](https://github.com/newrelic-forks/repolinter/commit/57c0dfd46a61a674d80455727ae5805a627acd7a))
* fix path seperator in symlink detection ([3898ed5](https://github.com/newrelic-forks/repolinter/commit/3898ed5b95d772f3b759e1c3c9c995aee3d7c757))
* fix pathing issues and succeed/fail criteria with no files found ([c0c101b](https://github.com/newrelic-forks/repolinter/commit/c0c101b2871abb4df584b6ce6cb76aeda3c8eb0a))
* jsdoc initial rules ([d200c51](https://github.com/newrelic-forks/repolinter/commit/d200c515ac2bb3aeab91c629e11954cd27b76ca7))
* minor updates to the markdown formatter ([#180](https://github.com/newrelic-forks/repolinter/issues/180)) ([45ee596](https://github.com/newrelic-forks/repolinter/commit/45ee596ef69947319278e2fcbfedd18c2d284aed))
* move command-exists to dependencies ([72abd8a](https://github.com/newrelic-forks/repolinter/commit/72abd8aca38cce124546231ec874fd07256fffbd))
* remove accidental shadowing of fs ([d5d6359](https://github.com/newrelic-forks/repolinter/commit/d5d63598f677d041fe2a79fdac63c5b76903a677))
* remove lstat check, fix flakey fs tests ([a154a89](https://github.com/newrelic-forks/repolinter/commit/a154a897ac113b104cb816d1f0296934cba4d15d))
* remove npm from plugins ([a628f6c](https://github.com/newrelic-forks/repolinter/commit/a628f6c5d483f357b8a67fa7a3d86e102d86f681))
* remove Object.fromEntries for node 10 support ([0644374](https://github.com/newrelic-forks/repolinter/commit/0644374c596f4e770e1d440f3980cd760ef9aa82))
* schema $id mixup. ([6bc0828](https://github.com/newrelic-forks/repolinter/commit/6bc08284d3ba10d3e29b77a54ab0bf7cf0d5645c))
* strip quotes from stringified content ([5222510](https://github.com/newrelic-forks/repolinter/commit/52225100c8cf8c61a0f50d981100cf8528063b49))
* switch to canonical broken-link-checker ([#205](https://github.com/newrelic-forks/repolinter/issues/205)) ([e62d767](https://github.com/newrelic-forks/repolinter/commit/e62d767dc299c503d04ff61da6433fede6899eb8))
* undo change ([cd23a3a](https://github.com/newrelic-forks/repolinter/commit/cd23a3a264870117fb992f7611c9ea6ada6f7473))
* undo change ([33d6384](https://github.com/newrelic-forks/repolinter/commit/33d63841fe6f0cc6560238b084aa99761957bc8f))
* update action to semantic-relase v19.0.5 is used ([b043a24](https://github.com/newrelic-forks/repolinter/commit/b043a248d5e3128d3bf27c726a418d79fa8afc82))
* update axioms, fixes and rules for documentation ([7432dfe](https://github.com/newrelic-forks/repolinter/commit/7432dfef156cc81aa90472726da95cb1e5079ad7))
* update base image ([1d0a938](https://github.com/newrelic-forks/repolinter/commit/1d0a938cd4060ac14cf550c174608dc531af5b61))
* update dockerfile to fix bad copying ([#224](https://github.com/newrelic-forks/repolinter/issues/224)) ([92389be](https://github.com/newrelic-forks/repolinter/commit/92389bec927d91c0220dd0f9f01d7c1a0c1148be))
* update dockerfile to reconfigure bundle which (may) have caused some bugs on linux ([889da3e](https://github.com/newrelic-forks/repolinter/commit/889da3ebf7475073726799a48b2a370798244af0))
* update github-markup to remove python2 dependency ([#209](https://github.com/newrelic-forks/repolinter/issues/209)) ([0c7c50c](https://github.com/newrelic-forks/repolinter/commit/0c7c50c41b620f876d1da84318800a9dde9cc9d6))
* update JSON schema URLs to point to TODOGroup repo ([9d397ef](https://github.com/newrelic-forks/repolinter/commit/9d397ef8d200f4f637c1a9218fbefcf8df954ce5))
* update test case for 'fail-on-non-existent' scenario, the 'passed' of non-exist file should depend on the parameter. ([e31bfb3](https://github.com/newrelic-forks/repolinter/commit/e31bfb32cd333a577c1d3ff6657ee55fb0ebe2c6))
* upgrade broken-link-checker to add node 10 support ([4f00b33](https://github.com/newrelic-forks/repolinter/commit/4f00b33c0e27d8a6bdad7c4ca6e00fe57ec94d90))
* upgrade ruby gems to latest version ([e36c10a](https://github.com/newrelic-forks/repolinter/commit/e36c10a9755a09c538d5dcc483c30f2e1b73c91a))
* windows compatibility fixes ([8fc0540](https://github.com/newrelic-forks/repolinter/commit/8fc05402b39fe7c3fd12fe1b2407abf0552631b5))
* windows fixes ([d52353e](https://github.com/newrelic-forks/repolinter/commit/d52353e381e518b9a966f71ee2ae8c05100945f0))


### Features

* add 'files-not-contents' rule to make string detection rulesets easier to maintain. ([093afc3](https://github.com/newrelic-forks/repolinter/commit/093afc30f78bf53fc0fb5c15a103df17b045e542))
* add better regex context support for file-contents ([2ff65d1](https://github.com/newrelic-forks/repolinter/commit/2ff65d1b88d2ca7d2d087157f9a91df83f6a9470))
* add file-not-exists rule ([184b787](https://github.com/newrelic-forks/repolinter/commit/184b78761af1e40b3200a885ede60b5e3d263d84))
* add file-not-exists rule ([#183](https://github.com/newrelic-forks/repolinter/issues/183)) ([ebca0b1](https://github.com/newrelic-forks/repolinter/commit/ebca0b1215aa8d57aad511da41263c7ac265887b))
* add file-remove fix ([04743ce](https://github.com/newrelic-forks/repolinter/commit/04743ce2b90f251a8830ca6e3610d84ba469d982))
* add file-remove fix ([#181](https://github.com/newrelic-forks/repolinter/issues/181)) ([ee913b3](https://github.com/newrelic-forks/repolinter/commit/ee913b3cb34d1233c256fa1a26db3562a640dc87))
* add files-not-hash rule for files detections. ([d2f262a](https://github.com/newrelic-forks/repolinter/commit/d2f262ab729f9f8117b7296be0478b9d4be63ab6))
* add large file rules ([2e48a85](https://github.com/newrelic-forks/repolinter/commit/2e48a857771402db1c33daee73bf5a47d9c280be))
* add lines of regex match in the file-contents and file-not-contents rule output, default turned off. ([9831684](https://github.com/newrelic-forks/repolinter/commit/983168407c7d8b9bae76107aacb55513b4dc3a49))
* add policyUrl and policyInfo in the default output. ([fb81866](https://github.com/newrelic-forks/repolinter/commit/fb81866ad095dadf8258d150de3e875deff90e93))
* add support for inheriting rulesets ([#207](https://github.com/newrelic-forks/repolinter/issues/207)) ([ca1ae01](https://github.com/newrelic-forks/repolinter/commit/ca1ae01996bbf30c687126fe51d84c4f2b979f7e)), closes [#21](https://github.com/newrelic-forks/repolinter/issues/21)
* add YAML support in config ([fb6c743](https://github.com/newrelic-forks/repolinter/commit/fb6c743e9fc0374ad16207e98ee748b030d4b728))
* finalize no broken links rule and dockerfile ([c1b1f72](https://github.com/newrelic-forks/repolinter/commit/c1b1f721c788894bb2cb59044fb9740c7f01d9ea))
* merge contributor-count axiom into fork ([f3dc857](https://github.com/newrelic-forks/repolinter/commit/f3dc857194456a66af7a2407c584aabd40116b18))
* **no-broken-links:** add option to pass or not pass in external links ([aaa92f8](https://github.com/newrelic-forks/repolinter/commit/aaa92f8e083c9e84ab4882f63cb905669f129930))
* switch to fork of broken-link-checker ([7df3086](https://github.com/newrelic-forks/repolinter/commit/7df308645ab883d70da15ac70e054e56a8a5628e))
* update dockerfile to reflect new dependencies ([c256af7](https://github.com/newrelic-forks/repolinter/commit/c256af7cdb682bdd4880577207f40446c8ede640))
* WIP adding a broken link checker rule ([9e8bb98](https://github.com/newrelic-forks/repolinter/commit/9e8bb98e34f55a52359fbbfa1a85071d9548f4d1))

## [0.11.2](https://github.com/todogroup/repolinter/compare/v0.11.1...v0.11.2) (2021-09-27)


### Bug Fixes

* update dockerfile to fix bad copying ([#224](https://github.com/todogroup/repolinter/issues/224)) ([92389be](https://github.com/todogroup/repolinter/commit/92389bec927d91c0220dd0f9f01d7c1a0c1148be))

## [0.11.1](https://github.com/todogroup/repolinter/compare/v0.11.0...v0.11.1) (2021-04-14)


### Bug Fixes

* update github-markup to remove python2 dependency ([#209](https://github.com/todogroup/repolinter/issues/209)) ([0c7c50c](https://github.com/todogroup/repolinter/commit/0c7c50c41b620f876d1da84318800a9dde9cc9d6))

# [0.11.0](https://github.com/todogroup/repolinter/compare/v0.10.1...v0.11.0) (2021-04-14)


### Features

* add support for inheriting rulesets ([#207](https://github.com/todogroup/repolinter/issues/207)) ([ca1ae01](https://github.com/todogroup/repolinter/commit/ca1ae01996bbf30c687126fe51d84c4f2b979f7e)), closes [#21](https://github.com/todogroup/repolinter/issues/21)

## [0.10.1](https://github.com/todogroup/repolinter/compare/v0.10.0...v0.10.1) (2021-03-25)


### Bug Fixes

* switch to canonical broken-link-checker ([#205](https://github.com/todogroup/repolinter/issues/205)) ([e62d767](https://github.com/todogroup/repolinter/commit/e62d767dc299c503d04ff61da6433fede6899eb8))

# [0.10.0](https://github.com/todogroup/repolinter/compare/v0.9.0...v0.10.0) (2020-12-30)


### Bug Fixes

* add missing github-markup dependencies to dockerfile ([b5fb88a](https://github.com/todogroup/repolinter/commit/b5fb88ad4c763dcb2c693a2a41b7ce3b2f183bcf))
* file-hash now accepts legacy configuration format ([d509274](https://github.com/todogroup/repolinter/commit/d50927423c965054d154adb56aaf1c48db778182))
* fix broken link behavrior with files in subdirectories ([6c14db9](https://github.com/todogroup/repolinter/commit/6c14db9fb7348fd42b72bc4ffc4ef7e4d6376409))
* fix pathing issues and succeed/fail criteria with no files found ([c0c101b](https://github.com/todogroup/repolinter/commit/c0c101b2871abb4df584b6ce6cb76aeda3c8eb0a))
* remove Object.fromEntries for node 10 support ([0644374](https://github.com/todogroup/repolinter/commit/0644374c596f4e770e1d440f3980cd760ef9aa82))
* update dockerfile to reconfigure bundle which (may) have caused some bugs on linux ([889da3e](https://github.com/todogroup/repolinter/commit/889da3ebf7475073726799a48b2a370798244af0))
* upgrade broken-link-checker to add node 10 support ([4f00b33](https://github.com/todogroup/repolinter/commit/4f00b33c0e27d8a6bdad7c4ca6e00fe57ec94d90))
* upgrade ruby gems to latest version ([e36c10a](https://github.com/todogroup/repolinter/commit/e36c10a9755a09c538d5dcc483c30f2e1b73c91a))


### Features

* finalize no broken links rule and dockerfile ([c1b1f72](https://github.com/todogroup/repolinter/commit/c1b1f721c788894bb2cb59044fb9740c7f01d9ea))
* update dockerfile to reflect new dependencies ([c256af7](https://github.com/todogroup/repolinter/commit/c256af7cdb682bdd4880577207f40446c8ede640))
* **no-broken-links:** add option to pass or not pass in external links ([aaa92f8](https://github.com/todogroup/repolinter/commit/aaa92f8e083c9e84ab4882f63cb905669f129930))
* switch to fork of broken-link-checker ([7df3086](https://github.com/todogroup/repolinter/commit/7df308645ab883d70da15ac70e054e56a8a5628e))
* WIP adding a broken link checker rule ([9e8bb98](https://github.com/todogroup/repolinter/commit/9e8bb98e34f55a52359fbbfa1a85071d9548f4d1))

# Changelog

## 1.0.0

### Breaking Changes

- The ruleset configuration format has been upgraded to [version 2](./README.md#creating-a-ruleset), including adding a [JSON schema](./rulesets/schema.json) and support for YAML. The previous ruleset format is still supported, however it is recommended that you translate your rulesets for this upgrade.
- Major changes have been made to the `lint` function:
  - Formatting and printing have been moved outside `lint`, allowing the developer to suppress or modify the output as needed. This change is reflected in the new [CLI implementation](./bin/repolinter.js).
  - The object returned by lint (`LintResult`) has been completely restructured.
  - A `dryRun` parameter has been added to disable fixes.
  - `async` was added to the function interface.
- Major changes have been make to the [JSON Formatter](index.js) to accommodate the structure change of `LintResult`.
- Non top-level configuration support (ex. `targetdir/otherdir/repolinter.json` would trigger another lint of `otherdir`) has been removed for now.
- Renamed several rule options to more clearly convey functionality (`files` -> `globsAny`) and remove problematic language (`blacklist` -> `denylist`). Backwards compatibility for old property names in version 1 rulesets is still maintained, however the schema will fail to validate in version 2.
- Some slight changes have been made to the default formatter to accommodate the feature list below.

### Features

- [Automatic fixes](./docs/fixes.md) have been added. These fixes must be [configured in your ruleset](./README.md#rules) before they can be used, but are otherwise enabled by default.
- [Markdown formatting](README.md#formatting-the-output) is now supported via a CLI argument.
- CLI argument parsing has re-implemented with [Yargs](https://github.com/yargs/yargs) to allow for a more user-friendly experience. All previous commands and arguments remain, and the following new options are now available:

  - `--dryRun`/`-d` - Disable fixes.
  - `--allowPaths`/`-a` - Specify an allowlist that repolinter should limit itself to.
  - `--rulesetFile`/`-r` - Manually specify the configuration repolinter should use.
  - `--rulesetUrl`/`-u` - Specify a URL where repolinter can retrieve the ruleset from.
  - `--format`/`-f` - Change the output format.

  For more information on these options please see the [Repolinter CLI](./bin/repolinter.js).

- Added several other functions to the Node API: `runRuleset`, `determineTargets`, `validateConfig`, and `parseConfig`.
- Added TypeScript types for the Node API.
- Add numerical comparison support for axioms and the [`contributor-count`](./docs/axioms.md#contributor-count) axiom.

### Fixes

- All file-based operations have been moved to `fs.promises`, which increased performance by a factor of 10.
- Fixed some issues with Windows paths.
- Updated NPM dependencies.
- Added more tests and [autogenerated documentation](https://todogroup.github.io/repolinter/).
