# Bootstrap Component Dependencies
Documenting the required file import dependencies for Bootstrap 4 components

## SCSS

### Always required imports

Import these after any variable customisation and map additions, but before any map removals (e.g. `$theme-colors: map-remove($theme-colors, "info", "light", "dark");`).

|Component|Dependencies|Notes|
|---|---|---|
|All|@import "bootstrap/scss/functions";<br />@import "bootstrap/scss/variables";<br />@import "bootstrap/scss/mixins";|

### Optional component-agnostic imports

Import these after any map removals (e.g. `$theme-colors: map-remove($theme-colors, "info", "light", "dark");`).

|Component|Dependencies|Notes|
|---|---|---|
|All|@import "bootstrap/scss/root";|Export colours, breakpoints and font families as CSS variables.|
|All|@import "bootstrap/scss/reboot";|Customised fork of Normalize.css.|
|All|@import "bootstrap/scss/type";|Typography (headings, hr, emphasis, lists).|
|All|@import "bootstrap/scss/images";|Responsive images (ensure images don't scale beyond their parents).|
|All|@import "bootstrap/scss/code";|Code formatting.|
|All|@import "bootstrap/scss/grid";|Grid layout (containers, row, col classes).|

### Layout

### Content

### Components

### Utilities
