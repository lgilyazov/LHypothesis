fastlane documentation
----

# Installation

Make sure you have the latest version of the Xcode command line tools installed:

```sh
xcode-select --install
```

For _fastlane_ installation instructions, see [Installing _fastlane_](https://docs.fastlane.tools/#installing-fastlane)

# Available Actions

## iOS

### ios patch

```sh
[bundle exec] fastlane ios patch
```

Release a new version with a patch bump_type

### ios minor

```sh
[bundle exec] fastlane ios minor
```

Release a new version with a minor bump_type

### ios major

```sh
[bundle exec] fastlane ios major
```

Release a new version with a major bump_type

### ios lib_lint

```sh
[bundle exec] fastlane ios lib_lint
```

Library lint

### ios code_coverage

```sh
[bundle exec] fastlane ios code_coverage
```

Create code coverage report

### ios complete_release

```sh
[bundle exec] fastlane ios complete_release
```

Complete release. Create tag and push pod

----

This README.md is auto-generated and will be re-generated every time [_fastlane_](https://fastlane.tools) is run.

More information about _fastlane_ can be found on [fastlane.tools](https://fastlane.tools).

The documentation of _fastlane_ can be found on [docs.fastlane.tools](https://docs.fastlane.tools).
