# Contributing

Bug reports, fixes and new ideas are welcome, in the repository they're about. Open an issue before starting on something large.

Clone the repository you want to change. Each one works on its own, and its README says how to run its tests and try a change in a real site. Before you open a pull request, run its tests and, if you touched the admin, its typecheck.

Two things the code expects:

- **The product's name is data.** Use `{brand}` or `:brand` in translated strings, `cms_brand()` in PHP and `brand()` in the admin.
- **Plugins only depend down,** on the core and other plugins. The core never names a plugin's classes.

A change people can see or use gets a line under `## Unreleased` in the changelog.

By contributing, you agree that your contribution is licensed under the MIT licence.
