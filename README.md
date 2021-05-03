# any-vega

Bundle of all [Vega](https://vega.github.io/vega) and [Vega-Lite](https://vega.github.io/vega-lite) packages; select the proper one for each mediatype.

## Installation

To run the commands in this repo, you should have `yarn` installed.

From source: `yarn install`

## Technical Contributions

To build from source: `yarn build`

To package using webpack: `yarn bundle`

To run tests: `yarn test`

### To add a new version of Vega or Vega-Lite

Create a directory inside of packages using the naming convention:
`vg{vega version}vl{vega-lite version}`. For example, Vega 5 and Vega-Lite 5
would be named `vg5vl5`.
