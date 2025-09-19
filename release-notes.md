﻿# Release Notes

## 1.23.0

_September 19, 2025_

- Fixed a bug where moving components from a form into the CollectionEditor did not work.

## 1.22.0

_April 15, 2025_

- Now the toolbar of the component is shown only when the mouse hovers over the component itself, so that different
  toolbars do not overlap each other.

## 1.21.0

_January 21, 2025_

- Fixed a bug that caused custom controls to not be supported in CollectionEditor.
-
## 1.20.0

_November 14, 2024_

- Fixed a bug that caused the entered value and an empty string in the DateTimePicker to be processed incorrectly.

## 1.19.0

_November 8, 2024_

- Fixed a bug that caused an empty string in the DatePicker to be processed incorrectly.

## 1.18.0

_October 18, 2024_

- Fixed a bug that caused values of hidden fields to be added to form data

## 1.17.0

_October 7, 2024_

- Fixed a bug where error classes were not applied to the `Radio group` component

## 1.16.0

_September 3, 2024_

- Fixed a bug where the `required` validation did not work after clearing the value in the `Dropdown` component with the `multiple` option

## 1.15.0

_August 8, 2024_

- Added support for Node.js 20.10
- Fixed a bug where the error tooltip was not displayed on the `Radio group` component

## 1.14.0

_August 9, 2023_

- Added ability to sort Dropdown items in alphabetical order

## 1.13.0

_June 8, 2023_

- Fix a corrupted file download

## 1.12.0

_June 2, 2023_

- Add onDownloadFail event to Files control

## 1.11.0

_May 12, 2023_

- Fix bug with Dropdown options

## 1.10.0

_April 17, 2023_

- Provision to show custom columns in Files control
- Improved compatibility with React 18
- Bug fix and minor improvements

## 1.9.0

_February 7, 2023_

- Bug fix and minor improvements

## 1.8.9

_February 6, 2023_

- Fix nested controls validation conditions checking
- Bug fix and minor improvements

## 1.8.8

_January 17, 2023_

- Bug fix and minor improvements

## 1.8.7

_January 12, 2023_

- The SemanticUI control for the input with the "time" type has been replaced with a standard one

## 1.8.6

_September 28, 2022_

- Added download timeout to configuration settings

## 1.8.5

_June 21, 2022_

- Added a property for editing HTML attributes of elements

## 1.8.4

_April 21, 2022_

- Bug fix and minor improvements

## 1.8.3

_April 1, 2022_

- Improve adaptation for large screen sizes
- Prevent validation for hidden (by visibility-condition) controls

## 1.8.2

_December 3, 2021_

- Bug fix and minor improvements

## 1.8.1

_November 30, 2021_

- Bug fix and minor improvements

## 1.8

- Added possibility to change tabs in Tab control
- The Files control now supports validation and can be disabled
- Bug fix and minor improvements

## 1.7

- Camera and Signature controls have been added.
- Minor improvements.

## 1.6

- Separation of basic functionality and library of controls (SemanticUI).
- Minor improvements.

## 1.5

- Printing forms feature.
- New features for creating forms by repeater and container controls

## 1.4

- New FormBuilder design.

## 1.3

- Some minor bugs have been fixed.

## 1.2

- New collection component Repeater added. It draws a specified set of components for each collection entity and supports server paging.
- Settings for adaptive layout added for components. For example there can be 2 components in the form which display the same list - grid and repeater. You can set the grid to be displayed in the desktop mode, and repeater to be displayed in the mobile mode. If component is not displayed, it is not rendered, that is why even if there are 2 heavy components on the page, it does not affect performance.
- Component can be bound to any Property Name from form data.
- Substitutions now work in component collections. Use {row.propertyName} expression to access current item data.
- Dates and numbers formatting added in substitutions. For example, {row.TransitionTime:DD.MM.YYYY HH:mm:ss} or {Amount:0,000.00}. moment.js is used to format dates. numeral.js is used to format numbers. If you need to use the formatting string set in localization, write {row.TransitionTime:local}.
- Interface performance optimized.

## 1.1

- Some minor bugs have been fixed.

## 1.0

- The first release of OptimaJet FormBuilder.
