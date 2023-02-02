# developer-guidelines

Guidelines for development

## git

**Npm versions and git tags:**

Changing the version should be done with `npm version <new-version>` instead of using `git tag ...`.
This will adjust the version in `package.json` AND create a new git commit including the appropriate tag.

**Push git tags:**

To push tags added with the above method, use `git push --follow-tags`.
