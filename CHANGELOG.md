# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## [4.4.1](https://github.com/styled-components/jest-styled-components/compare/v4.4.0...v4.4.1) - 2017-08-19
### Fixed
- [toMatchSnapshot] Avoid using non-hashes class names when generating snapshots.

## [4.4.0](https://github.com/styled-components/jest-styled-components/compare/v4.3.0...v4.4.0) - 2017-08-11
### Added
- [toMatchSnapshot] Add `modifier` option to search for pseudo classes and attributes.

## [4.3.0](https://github.com/styled-components/jest-styled-components/compare/v4.2.2...v4.3.0) - 2017-07-31
### Added
- [toMatchSnapshot] Accept a third options parameter to search for rules nested within At-rules.

## [4.2.2](https://github.com/styled-components/jest-styled-components/compare/v4.2.1...v4.2.2) - 2017-07-24
### Fixed
- [toMatchSnapshot] Handle non Styled Components class names with leading white spaces.

## [4.2.1](https://github.com/styled-components/jest-styled-components/compare/v4.2.0...v4.2.1) - 2017-07-23
### Fixed
- [toMatchSnapshot] Handle class names with trailing white spaces.

## [4.2.0](https://github.com/styled-components/jest-styled-components/compare/v4.1.2...v4.2.0) - 2017-07-20
### Changed
- [toHaveStyleRule (React)] Accept regular expressions as a second parameter.

## [4.1.2](https://github.com/styled-components/jest-styled-components/compare/v4.1.1...v4.1.2) - 2017-07-20
### Fixed
- [toHaveStyleRule (React)] Avoid showing Enzyme errors when class names are not present in the tree.

## [4.1.1](https://github.com/styled-components/jest-styled-components/compare/v4.1.0...v4.1.1) - 2017-07-20
### Fixed
- [toMatchSnapshot] Fix regression introduced in 4.1.0 which broke the support for Styled Components < 2.

## [4.1.0](https://github.com/styled-components/jest-styled-components/compare/v4.0.3...v4.1.0) - 2017-07-20
### Changed
- [toMatchSnapshot] Preserve custom (i.e. not generated by Styled Components) class names.

## [4.0.3](https://github.com/styled-components/jest-styled-components/compare/v4.0.2...v4.0.3) - 2017-07-18
### Fixed
- [toMatchSnapshot] Collect unique class names and avoid skipping indexes in placeholders.
- [toHaveStyleRule (React)] Support `null` components.

## [4.0.2](https://github.com/styled-components/jest-styled-components/compare/v4.0.1...v4.0.2) - 2017-07-17
### Fixed
- [toMatchSnapshot] Make the replace regular expression less greedy (i.e. stop at the first match).

## [4.0.1](https://github.com/styled-components/jest-styled-components/compare/v4.0.0...v4.0.1) - 2017-07-16
### Fixed
- [toMatchSnapshot] Replace class names inside the `className` attribute only.

## [4.0.0](https://github.com/styled-components/jest-styled-components/compare/v3.3.2...v4.0.0) - 2017-07-15
### Added
- [toMatchSnapshot] Replace class names generated by Styled Components with placeholders.

### Changed
- Update projects dependencies.
- Improve README.
- Format code with Prettier.
- Refactor folders and tests.

### Removed
- Remove `toMatchStyledComponentsSnapshot` matcher.
