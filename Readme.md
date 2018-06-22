# Live templates for JS Modules

The set of shortcuts for common module import and export expressions

![demo](demo.gif)

## Included templates

**ES6**

* **imf** - `import module from 'module'`
* **edc** - `export default class className`
* **edf** - `export default function functionName() {}`

**Commonjs**

* **csr** - `const { value } = require('module')`
* **mde** - `module.exports = value`

Templates will try to provide varialbe name according to the current file name.

## Installation

Paste the content of the [templates.xml](templates.xml) on the `Settings -> Preferences -> Live templates` tab.

Documentation about [live templates](https://www.jetbrains.com/idea/help/sharing-live-templates.html) on IntelliJ website.
