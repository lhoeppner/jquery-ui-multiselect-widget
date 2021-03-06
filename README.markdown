# jQuery UI MultiSelect Widget with option columns

MultiSelect progessively enhances an ordinary multiple select control into elegant drop down list of checkboxes, stylable with ThemeRoller.  

Changes to original version:
- customized to display option columns using a table instead of ul
- defined within a require module for use in an AMD context
- 'change' event is only triggered when the dropdown closes, NOT when an input selection changes

This is NOT a release version (among other things, option groups don't work yet).

Currently this has REQUIRED parameters:

- columns: array of objects that define the columns (object format: { column: 'myColumn', title: 'My column header' }
- rows: array of arrays, one array per row, each row array with a value for each column
- columnSize: width of each column in px

![Example](https://github.com/lhoeppner/jquery-ui-multiselect-widget/blob/master/screenshot.gif?raw=true)