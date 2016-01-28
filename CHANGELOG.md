# Changelog

## unreleased
Nothing yet

- - -

## 0.9.0 (2016-01-28)
* Added alerts pattern

- - -

## 0.8.12 (2016-01-26)
* FIX- Removed unused %btn-base extend from buttons

- - -

## 0.8.11 (2016-01-26)
* Removed unused %btn-base extend from buttons

- - -

## 0.8.10 (2016-01-26)
* Remove unused .list-links/%list-links rules.

- - -

## 0.8.9 (2016-01-26)
* removing reference to deleted %reset-copy utility

- - -

## 0.8.8 (2016-01-26)
* Remove demo directory from the public packages.

- - -

## 0.8.7 (2016-01-25)
* Removed pointer from progress bar hover

- - -

## 0.8.6 (2016-01-22)
* Revised ltr/rtl config and settings to not rely on Sass @import + @if

- - -

## 0.8.5 (2016-01-13)
* Added a new element, Lists - for use in content and simple navigation

- - -

## 0.8.4 (2016-01-13)
* bulletproofing text/base link styling

- - -

## 0.8.3 (2016-01-13)
* updating spacing maps to use vert/horiz vars

- - -

## 0.8.2 (2016-01-08)
* removing unused animate.css package from dependencies (for optimization/simplification's sake)

- - -

## 0.8.1 (2016-01-04)
* adding system utility-based information color (and range) - to be used on educational, informational, and note-based UI elements

- - -

## 0.8.0 (2016-01-02)
* renaming button types to suggest more visual styling in nature
* simplifying classes needed to reference buttons
* removing extraneous visual button styles (elevated alt)
* revising combo/button group styling and architecture
* abstracting out buttons into Sass placeholders to extend (matching how we have architected other patterns)

- - -

## 0.7.5 (2015-12-29)
* simplifying and standardizing copy element syntax

- - -

## 0.7.4 (2015-12-29)
* correcting styling for disabled enhanced radio button

- - -

## 0.7.3 (2015-12-22)
* adding transparent options to base and utility color palettes and remove unused colors partial

- - -

## 0.7.2 (2015-12-17)
* correcting doc/depedency small errors with npm package

- - -

## 0.7.1 (2015-12-16)
* ignoring files in npm package

- - -

## 0.7.0 (2015-12-14)
* Moving from Bower-based to NPM-based package management

- - -
## 0.6.0 (2015-11-24)
* Revising color patterns to use Sass mix() method

- - -

## 0.5.0 (2015-11-06)
* Reconfigured preset Sass organization and compilation to make customization of patterns easier. Core utilities and set up are now called in one Sass partial. Patterns now define scoped settings they need.
* Cleaned up formatting and terminology within Sass inline documentation

- - -

## 0.4.5 (2015-11-03)
* Locked version of bi-app-sass bower dependency to 1.1.0.

- - -

## 0.4.4 (2015-11-02)
* Removed specific font-family declarations on headings/copy/form elements in favor of inheritance from _reset.scss's body rule (for easier customizations/overrides).

- - -

## 0.4.3 (2015-10-28)
* Added text truncation and wrapped Sass placeholders
## 0.4.3 (2015-11-02)
* Removed specific font-family declarations on headings/copy/form elements in favor of inheritance from _reset.scss's body rule (for easier customizations/overrides).

- - -

## 0.4.2 (2015-10-23)
* Removed _colors.scss as a main pattern (since it was only providing supportive styling for the documentation site) and placed its rules within the documentation site's Sass.

- - -

## 0.4.1 (2015-10-23)
* Re-organized edx-icons SVG image fallbacks to be part of pattern-library package
* Optimized edx-icons SVG image files
* Automated fallback rules for edx-icons

- - -

## 0.4.0 (2015-10-20)

* syncs up variable naming standards with several already set variables (buttons and forms primarily)
* plumbs through variables to be used consistently in future theming where they weren't set (base resets and buttons)
* abstracts out a few variables that were being used in unconventional or out of scope ways
* simplifies button-based rules for easier maintenance and for Sass extension

- - -

## 0.3.3 (2015-10-18)
* creating pre-compiled static CSS versions of pattern-library base styling for use within external apps

- - -

## 0.3.2 (2015-10-16)
* switched to using the term 'pattern' rather than 'element' for clarity throughout docs and UI

- - -

## 0.3.1 (2015-10-16)
* Removed not used svg4everybody bower component (see 0.3.0)

- - -

## 0.3.0 (2015-10-09)
* Converted icon rendering to be font-based with A Font Garde-supported fallbacks

- - -

## 0.3.1 (2015-10-14)
* updating bower package prefs to ignore moved pldoc assets

- - -

## 0.3.0 (2015-10-09)
* Converted icon rendering to be font-based with A Font Garde-supported fallbacks

- - -

## 0.3.0 (2015-10-01)
* Cleaned up variables: abstraction, scope, and simplification

- - -

## 0.2.6 (2015-09-04)
* Moved SVG-based icons to icons directory rather than images

- - -

## 0.2.5 (2015-09-02)
* Abstracted specific font-face paths for customization

- - -

## 0.2.4 (2015-09-02)
* Adjusted small breakpoint, and adjust margin on doc site for small screens
* Simplified edx-pattern-library sass compilation syntax
* Simplified paths in edx-pattern-library bower package
* Added third party and general dependencies to README

- - -

## 0.2.0 (2015-08-31)
* Packaged UX Pattern Library source code as a bower package
* Added supporting documentation for contributing, changelog, and authors

- - -

## 0.1.0 (2015-03-31)
* Intitial release
