# Deno timer bug test

The tests run way slower in Deno compared to Node. The likely culprit is `setImmediate`.

## Steps to reproduce

1. Clone this repo
2. Run `deno run -A npm:mocha`

To compare this with node:

1. Run `npm i`
2. Run `npx mocha`
