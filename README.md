# Licenses

Noodling on license advertisements.

This repository is for texts describing the contribution terms of repositories for WGs, CGs, IGs governed by the W3C process and licenses.

To use these licenses, put the relevant pair of documents (contributing and license) into the root of a repository as `CONTRIBUTING.md` and `LICENSE.md`.

## SPDX

Software or documentation that is packaged for [Node.js](https://nodejs.org/en/) and other platforms can benefit from machine-readable license information.
Visit [SPDX (Software Package Data Exchange)](https://spdx.org/) for more information, and check out
[the complete list of licenses](https://spdx.org/licenses/).

In a Node.js package, for example, you should have [a `license` key in your `package.json`](https://docs.npmjs.com/files/package.json#license),
and its value should be a valid SPDX string:

```json
{
  "name":    "foo",
  "version": "1.2.3",
  "license": "MIT"
}
```
