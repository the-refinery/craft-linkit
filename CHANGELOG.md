# Linkit Changelog
> One link field to rule them all, built for [Craft 3](http://craftcms.com)

## 1.1.11 - 2019-04-03

### Fixed

*   Fixed migration issue with Schema Checks & Mute events. Credit to @andris-sevcenko again.

## 1.1.10 - 2019-03-19

### Fixed

*   Fixed Craft 2 migration (findgers crossed for good) addressing issues with element sources and linkit fields nested in Matrix or Super Table. Thanks again @andris-sevcenko.
*   Fixed SuperTable Craft 2 migration issue where Linkit is installed before SuperTable during upgrade.
*   Fixed migration of Element sources converting IDs to UIDs.
*   Fixed custom link docs (Thanks @domstubbs)

## 1.1.9 - 2019-03-02

### Fixed

*   Fixed migration issue where Super Table was not setting a type value on a field. Thanks @olibon.

### Changed

*   Improved migration scripts (Thanks to @roelvanhintum's input)

## 1.1.8 - 2019-02-08

### Changed

*   Changed migration scripts as per Crafts new recommendations (Thanks to @andris-sevcenko)
*   Changed requires Craft 3.1.2+
*	Changed README.md installation instructions

### Fixed

*	Fixed some README.md typos

### Added

*   Added `{{ customText }}` info to the docs

## 1.1.6 - 2019-01-17

### Fixed

*	Fixed Craft 2 migration error preventing install on Craft 3.1.x
*   Removed some unused template tags
*   Fixed issues bug on the about page

## 1.1.5.1 - 2019-01-15

### Fixed

*	Fixed Changelog date

## 1.1.5 - 2019-01-14

### Added

*	Added support for @web alias in the URL link type
*	Added support for mailto links in the URL link type
*	Added settings to control whether the URL link type allows hashes, mailto, aliases or paths

## 1.1.4 - 2018-10-23

### Fixed

*   Fixed some recursive infinite loop issues and Solpace Calendar crashes (All credit goes to Craft's Brad Bell)

## 1.1.3 - 2018-09-28

### Changed

*   Changed - Version bump

## 1.1.2 - 2018-09-28

### Changed

*   Changed - Plugin icon

## 1.1.1 - 2018-08-23

### Fixed

*   Fixed a couple of changelog typos :)

## 1.1.0 - 2018-08-23

### Changed

*   Changed - Improved Linked In link validation
*   Changed - Improved url link validation
*   Changed - Element link types now allowed to select disabled elements to match the first party Craft element fieldtypes
*   Changed - Updated element select to match first party fields
*   Changed - Improved support for multisite setup

### Added

*   Added `hasElement()` method to link models to quickly determine if the link is an element link type
*   Added `isAvailable()` method to link models to quickly determine if a link is available
*   Added setting to override the default placeholder text for basic and social link types
*   Added `getTableAttributeHtmlLink()` method, Linkit fields are now previewable table columns in table view
*   Added status indicators to preview to determine if a link is available

### Fixed

*   Fixed issue with the Craft 2 normailize function when a type is not specified
*   Fixed cp translation bug on element link types when using multiple sites
*   Fixed an issue with the Craft 2 > Craft 3 migration script related to an undefined type index

## 1.0.8 - 2018-04-24

### Fixed

*   Fixed element select - now respects selected site in the cp

## 1.0.7.1 - 2018-04-24

### Added

*   Fixed version issue

## 1.0.7 - 2018-04-24

### Added

*   Added Craft 2 migration scripts
*   Added product link type (requires the awesome Craft Commerce)

### Fixed

*   Fixed email & phone links text value returning the full url
*   Fixed documentation link

## 1.0.6 - 2018-04-16

### Fixed

*   Fixed the select toggle where there is multiple Linkit field's on the same layout
*   Fixed the default text displaying incorrectly for element links

### Added

*   Added `getLinkAttributes()` to access any addional attributes set by Linkit
*   Added `getTargetString()` to access the current target setting `_self` or `_blank`

## 1.0.5 - 2018-03-31

*   Case fix - thanks Brad!

## 1.0.4 - 2018-03-30

*   Updated naming - thanks Brandon!

## 1.0.3 - 2018-03-27

*   Updated settings page to group link types.
*   Enabling link types is now done with lightswitches instead of checkboxes

## 1.0.2 - 2018-03-27

*   Updated icon and license.

## 1.0.0 - 2018-03-27

*   Initial release
