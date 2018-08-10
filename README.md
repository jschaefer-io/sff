# SFF
SFF is a small frontend library containing basic typo and form styles with an easy to extend SCSS-API.
It is not meant to be compiled without modifications to the default settings and therefore only provides the .scss files.

## SFF contains:
- Base styles
- Typography
- Buttons
- Forms
- Tables
- Responsive Flex-Grid
- Visibility Classes

## Customizing
Every variable in the default settings is marked as `!default` and can be overwritten without copying any files.
See [the main sff.scss file](https://github.com/jschaefer-io/sff/blob/master/src/sff.scss) for the list of all variables.

## Usage
Install with `npm install sff` and add `node_modules/sff/src` to your SASS include paths.

``` scss
// Load Settings and Modules
@import 'sff'; 

// Full Include
@include sff();

// Individual Include
@include sff_base();
@include sff_typo();
@include sff_form();
@include sff_button();
@include sff_table();
@include sff_flex();
@include sff_visibility();
```