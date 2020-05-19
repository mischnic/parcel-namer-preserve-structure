# `@mischnic/parcel-namer-preserve-structure`

Tries to retain the existing folder structure of your source files.

## Usage:

Add a `.parcelrc` into your root directory (next to `package.json`):

```json
{
	"extends": "@parcel/config-default",
	"namers": ["@mischnic/parcel-namer-preserve-structure", "..."]
}
```
