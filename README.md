# @digital-coupons/eslint-config

Our custom set of rules as eslint shareable configuration

## Included dependencies

ESLint does not allow to include in the shareable configurations it's
dependencies as part of the package forcing to have a peerDependencies section
and including those dependencies in the projects using this configurations.

* [ESLint shareable configs](https://eslint.org/docs/latest/developer-guide/shareable-configs)
* [Support having plugins as dependencies in shareable config](https://github.com/eslint/eslint/issues/3458)
* [@rushstack/eslint-patch](https://www.npmjs.com/package/@rushstack/eslint-patch)
