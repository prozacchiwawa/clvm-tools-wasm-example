@chia/chialisp usage example from node
====

From node you can just require @chia/chialisp like this

```javascript
const {h, t, Program} = require('@chia/chialisp');
```

This repo has a test rig set up.  You can run it like this:

```bash
$ yarn install
...
$ yarn test
yarn run v1.22.19
$ jest
 PASS  src/lib/tests/index.test.ts
  ✓ Has BLS signatures support (786 ms)
  ✓ Has the "h" function (1 ms)
  ✓ Converts to string (2 ms)
  ✓ Accepts already converted objects (3 ms)
  ✓ Has as_pair (3 ms)
  ✓ Has null (1 ms)
  ✓ Has listp (2 ms)
  ✓ Has nullp (2 ms)
  ✓ Has as_int (1 ms)
  ✓ Has as_bigint (2 ms)
  ✓ Has first and rest (3 ms)
  ✓ Has cons (3 ms)
  ✓ Has the t function (4 ms)
  ✓ Has as_bin (2 ms)
  ✓ Has list_len (3 ms)
  ✓ Has equal_to (4 ms)
  ✓ Has as_javascript (6 ms)
  ✓ Has run (2 ms)
  ✓ Has curry (11 ms)
  ✓ works as expected in context (72 ms)

Test Suites: 1 passed, 1 total
Tests:       20 passed, 20 total
Snapshots:   0 total
Time:        2.726 s
Ran all test suites.
Done in 3.75s.
```
