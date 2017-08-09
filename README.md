# Simplecov issue reproduction

Unloaded files have all lines classified as relevant, but whitespace / comments should not count towards code coverage.

This leads to the overall coverage being understated.

## Actual result:

![Actual result](actual.png)

Shows 5 relevant lines

## Expected result:

![Expected result](expected.png)

Shows 3 relevant lines
