# Change Log
All notable changes to this project will be documented in this file.
This project adheres to [Semantic Versioning](http://semver.org/).

## [Unreleased][unreleased]
- Removed view code to parse narratives as jsonp (now straight json)
- Added a url and view option to demo the landing page with a local json file
- Upgrade npm shrinkwrap endpoints to HTTPS

## [1.2.6] - 2016-10-06
- Copy updated for `submit-a-complaint` and `process`
- Added travis and coveralls setup
- Updated the download 4x4 codes for Money transfers

## [1.2.2] - 2016-06-06
### Fixed
- Fix 404 for link to Narrative Scrubbing Standard PDF

## [1.2.1] - 2016-05-26
### Changed
- Fix broken report links on data use page
- Add new reports to data use page
- Submit a complaint links to "Other financial services" now point to accurate form URLs with the correct radio buttons selected.

## [1.2] - 2016-04-21
### Changed
- Update header on Submit a Complaint to feature the phone number more prominently.
- Added Monthly complaint report, volumes 8 and 9
- Add snyk to project
- cf.gov v1 release: Tweaks needed to make sure 'pip wheel <repo> includes all files'

### Fixed
- Use `.webfont-regular()` mixin for `.block-label` so Windows users see Avenir Next correctly.

## [1.1.8] - 2016-02-25
### Changed
- Submit a complaint info for student loans now provides an option for submitting federal student loan complaints.

## [1.1.7] - 2016-02-23
### Added
- Bug fixes for Django static file paths
- Bug fixes for complaint database landing page: links to Socrata random complaint category views and tags loop comma madness

## [1.1.6] - 2016-02-22
### Added
- Copy updates to Submit a complaint page

## [1.1.5] - 2016-02-17
### Added
- Copy updates for Tags field on complaint database landing page and Data use page
- Fix Submit a complaint page title

## [1.1.4] - 2016-02-04
### Added
- Copy fixes on complaint database landing page
- Bug fixes for complaint database landing page "Download the data" section
- Add Monthly Complaint Report Volume 7 link to Reports section of Data use page

## [1.1.3] - 2016-01-27
### Added
- Fixes missing ID for "Reports" anchor link on complaint database landing page.

## [1.1.2] - 2016-01-25
### Added
- Copy fixes for the initial release of the complaint and complaint database sites.

## [1.1.1] - 2016-01-22
### Added
- Bug fixes for the initial release of the complaint and complaint database sites.

## [1.1.0] - 2016-01-11
### Added
- Initial release of the complaint and complaint database.

## 1.0.0 - 2015-12-04
### Added
- Version 1 Django app + Jinja templates


[unreleased]: ../../compare/v1.2.2...HEAD
[1.2.2]: ../../compare/v1.2.1...v1.2.2
[1.2.1]: ../../compare/v1.2...v1.2.1
[1.2]: ../../compare/v1.1.8...v1.2
[1.1.8]: ../../compare/v1.1.7...v1.1.8
[1.1.7]: ../../compare/v1.1.6...v1.1.7
[1.1.6]: ../../compare/v1.1.5...v1.1.6
[1.1.5]: ../../compare/v1.1.4...v1.1.5
[1.1.4]: ../../compare/v1.1.3...v1.1.4
[1.1.3]: ../../compare/v1.1.2...v1.1.3
[1.1.2]: ../../compare/v1.1.1...v1.1.2
[1.1.1]: ../../compare/v1.1.0...v1.1.1
[1.1.0]: ../../compare/v1.0.0...v1.1.0
