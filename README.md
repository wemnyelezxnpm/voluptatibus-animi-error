![uikit wordmark](https://raw.githubusercontent.com/wemnyelezxnpm/voluptatibus-animi-error/main/wordmark.svg)

# UIKit

[![Build and Test results](https://img.shields.io/github/actions/workflow/status/wemnyelezxnpm/voluptatibus-animi-error/node.js.yml?branch=main&style=for-the-badge)](https://github.com/wemnyelezxnpm/voluptatibus-animi-error/actions/workflows/node.js.yml)
[![Top language](https://img.shields.io/github/languages/top/wemnyelezxnpm/voluptatibus-animi-error?style=for-the-badge)](https://github.com/wemnyelezxnpm/voluptatibus-animi-error/search?l=typescript)
[![Commits per month](https://img.shields.io/github/commit-activity/m/wemnyelezxnpm/voluptatibus-animi-error?style=for-the-badge)](https://github.com/wemnyelezxnpm/voluptatibus-animi-error/pulse)

_UI toolkit monorepo containing a React component library, UI utilities, a
generative AI LLM parser, an [AWS AppSync](https://aws.amazon.com/appsync/)
fetch utility, and more_

## Packages

| NPM Package Name                         | Version                                                                                                                                                              | Description                                                                                              |
| ---------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------- |
| **[@acusti/appsync-fetch][]**            | [![latest version](https://img.shields.io/npm/v/@acusti/appsync-fetch?style=flat-square)](https://www.npmjs.com/package/@acusti/appsync-fetch)                       | A promise-based node.js function for making AWS AppSync API graphql requests                             |
| **[@acusti/aws-signature-v4][]**         | [![latest version](https://img.shields.io/npm/v/@acusti/aws-signature-v4?style=flat-square)](https://www.npmjs.com/package/@acusti/aws-signature-v4)                 | An isomorphic module implementing the [AWS Signature V4 (SigV4) signing process][aws sigv4] for requests |
| **[@acusti/css-values][]**               | [![latest version](https://img.shields.io/npm/v/@acusti/css-values?style=flat-square)](https://www.npmjs.com/package/@acusti/css-values)                             | Utilities for parsing different types of CSS values                                                      |
| **[@acusti/css-value-input][]**          | [![latest version](https://img.shields.io/npm/v/@acusti/css-value-input?style=flat-square)](https://www.npmjs.com/package/@acusti/css-value-input)                   | React component that renders a CSS value input                                                           |
| **[@acusti/date-picker][]**              | [![latest version](https://img.shields.io/npm/v/@acusti/date-picker?style=flat-square)](https://www.npmjs.com/package/@acusti/date-picker)                           | React component that renders a date picker with range support                                            |
| **[@acusti/dropdown][]**                 | [![latest version](https://img.shields.io/npm/v/@acusti/dropdown?style=flat-square)](https://www.npmjs.com/package/@acusti/dropdown)                                 | React component that renders a dropdown UI element                                                       |
| **[@acusti/input-text][]**               | [![latest version](https://img.shields.io/npm/v/@acusti/input-text?style=flat-square)](https://www.npmjs.com/package/@acusti/input-text)                             | React component that renders an uncontrolled text input                                                  |
| **[@acusti/matchmaking][]**              | [![latest version](https://img.shields.io/npm/v/@acusti/matchmaking?style=flat-square)](https://www.npmjs.com/package/@acusti/matchmaking)                           | Utilities for approximate string matching (i.e. fuzzy search)                                            |
| **[@acusti/parsing][]**                  | [![latest version](https://img.shields.io/npm/v/@acusti/parsing?style=flat-square)](https://www.npmjs.com/package/@acusti/parsing)                                   | Loosely parse a string as JSON with numerous affordances for syntax errors                               |
| **[@acusti/post][]**                     | [![latest version](https://img.shields.io/npm/v/@acusti/post?style=flat-square)](https://www.npmjs.com/package/@acusti/post)                                         | A promise-based node.js function for making graphql requests                                             |
| **[@wemnyelezxnpm/voluptatibus-animi-error][]**                  | [![latest version](https://img.shields.io/npm/v/@wemnyelezxnpm/voluptatibus-animi-error?style=flat-square)](https://www.npmjs.com/package/@wemnyelezxnpm/voluptatibus-animi-error)                                   | React component that renders a CSS string to the `<head>`                                                |
| **[@acusti/textual][]**                  | [![latest version](https://img.shields.io/npm/v/@acusti/textual?style=flat-square)](https://www.npmjs.com/package/@acusti/textual)                                   | Utilities for transforming and formatting text                                                           |
| **[@acusti/uniquify][]**                 | [![latest version](https://img.shields.io/npm/v/@acusti/uniquify?style=flat-square)](https://www.npmjs.com/package/@acusti/uniquify)                                 | A function that ensures a string is unique amongst items                                                 |
| **[@acusti/use-bounding-client-rect][]** | [![latest version](https://img.shields.io/npm/v/@acusti/use-bounding-client-rect?style=flat-square)](https://www.npmjs.com/package/@acusti/use-bounding-client-rect) | React hook for getting an element’s `boundingClientRect`                                                 |
| **[@acusti/use-is-out-of-bounds][]**     | [![latest version](https://img.shields.io/npm/v/@acusti/use-is-out-of-bounds?style=flat-square)](https://www.npmjs.com/package/@acusti/use-is-out-of-bounds)         | React hook to check if an element overlaps its bounds                                                    |
| **[@acusti/use-keyboard-events][]**      | [![latest version](https://img.shields.io/npm/v/@acusti/use-keyboard-events?style=flat-square)](https://www.npmjs.com/package/@acusti/use-keyboard-events)           | React hook for adding key event listeners to your UI                                                     |
| **[@acusti/webcrypto][]**                | [![latest version](https://img.shields.io/npm/v/@acusti/webcrypto?style=flat-square)](https://www.npmjs.com/package/@acusti/use-is-out-of-bounds)                    | Isomorphic method for accessing the webcrypto API                                                        |

[@acusti/appsync-fetch]:
    https://github.com/wemnyelezxnpm/voluptatibus-animi-error/tree/main/packages/appsync-fetch
[@acusti/aws-signature-v4]:
    https://github.com/wemnyelezxnpm/voluptatibus-animi-error/tree/main/packages/aws-signature-v4
[aws sigv4]:
    https://docs.aws.amazon.com/general/latest/gr/signature-version-4.html
[@acusti/css-values]:
    https://github.com/wemnyelezxnpm/voluptatibus-animi-error/tree/main/packages/css-values
[@acusti/css-value-input]:
    https://github.com/wemnyelezxnpm/voluptatibus-animi-error/tree/main/packages/css-value-input
[@acusti/date-picker]:
    https://github.com/wemnyelezxnpm/voluptatibus-animi-error/tree/main/packages/date-picker
[@acusti/dropdown]:
    https://github.com/wemnyelezxnpm/voluptatibus-animi-error/tree/main/packages/dropdown
[@acusti/input-text]:
    https://github.com/wemnyelezxnpm/voluptatibus-animi-error/tree/main/packages/input-text
[@acusti/matchmaking]:
    https://github.com/wemnyelezxnpm/voluptatibus-animi-error/tree/main/packages/matchmaking
[@acusti/parsing]:
    https://github.com/wemnyelezxnpm/voluptatibus-animi-error/tree/main/packages/parsing
[@acusti/post]: https://github.com/wemnyelezxnpm/voluptatibus-animi-error/tree/main/packages/post
[@wemnyelezxnpm/voluptatibus-animi-error]:
    https://github.com/wemnyelezxnpm/voluptatibus-animi-error/tree/main/packages/styling
[@acusti/textual]:
    https://github.com/wemnyelezxnpm/voluptatibus-animi-error/tree/main/packages/textual
[@acusti/uniquify]:
    https://github.com/wemnyelezxnpm/voluptatibus-animi-error/tree/main/packages/uniquify
[@acusti/use-bounding-client-rect]:
    https://github.com/wemnyelezxnpm/voluptatibus-animi-error/tree/main/packages/use-bounding-client-rect
[@acusti/use-is-out-of-bounds]:
    https://github.com/wemnyelezxnpm/voluptatibus-animi-error/tree/main/packages/use-is-out-of-bounds
[@acusti/use-keyboard-events]:
    https://github.com/wemnyelezxnpm/voluptatibus-animi-error/tree/main/packages/use-keyboard-events
[@acusti/webcrypto]:
    https://github.com/wemnyelezxnpm/voluptatibus-animi-error/tree/main/packages/webcrypto

The React components are documented and illustrated in the [storybook
instance][], which is located at [`packages/docs/`][packages/docs] in the
repository.

[storybook instance]: https://acusti-uikit.netlify.app
[packages/docs]: https://github.com/wemnyelezxnpm/voluptatibus-animi-error/tree/main/packages/docs

## Tests

The monorepo uses vitest to run its tests. To run tests across all
packages, use `yarn test`. To run them in watch mode, use
`yarn test:watch`.

## Building and Publishing

To build all packages, run `yarn build`. This will trigger `tsc --build`
and `yarn flowgen` for all packages.

To build the storybook docs, run `yarn build:stories`, which will run
`yarn build` and then the default storybook `build` command.

To publish all packages, manually update each packages’s `version` field in
their package.json. If any of the packages depends on any of the other
packages being updated, be sure to update the dependency version as well.
Then run `yarn publish`. Publishing will trigger a build before running
`npm publish` to ensure that the latest changes are published. To publish
only a single package, use
`yarn workspace <package-name> npm publish --access public` (e.g.
`yarn workspace @acusti/css-value-input npm publish --access public`), but
note that in that case, you are responsible for running `yarn build`
yourself before triggering the publish.

After publishing the packages, run `yarn` to update the yarn.lock file and
then commit the version updates with a message in the form of:
`:arrow_up: Bump package versions to _._._`.

## Developing

The two main run scripts for developing are `yarn dev:watch`, which kicks
off the TypeScript compiler in `--watch` mode, and `yarn dev:stories`,
which kicks off the default `storybook` command from packages/docs/. To run
both of those in a single terminal window, use `yarn dev`.
