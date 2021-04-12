# Four-Function Calculator

This is a simple four-function calculator (addition, subtraction, multiplication, and division). It may later be expanded to support more operations and to support multiple different calculator instances on the same page.

## Building

First, install [`npm`](https://www.npmjs.com/get-npm) if you don't already have it installed. This is used to manage the development environment: it will install and manage all the other tools and dependencies for this project.

To install the tools and dependencies, run `npm i` in your terminal.

There are some `npm` scripts set up for this project, which you can run in any terminal environment with `npm` installed.

- `npm run build` builds the project, outputting to the `build/` folder.
- `npm run docs` builds the HTML documentation for the project, outputting to the `docs/` folder.
- `npm run test` tests the project, outputting to the terminal.
- `npm run clean` removes all build artifacts.
- `npm run clean-deps` removes all build artifacts and all dependencies installed for the project.

Some of the scripts also have a "watcher" variants: `npm run build-watch`, `npm run docs-watch`, and `npm run test-watch`. These run continuously and watch for changes in the source files, automatically updating the output on each change.

## Running

Open the `build/index.html` file in any standard web browser that supports [ECMAScript 5](https://caniuse.com/es5) and [the CSS "flexbox" feature](https://caniuse.com/flexbox).
