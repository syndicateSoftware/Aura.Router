- Remove "custom" match/generate

- Use a PSR-3 logger instead of a debug stack

- actually convert to PSR-7

- Can we avoid AbstractSpec?

- Make route immutable?

- Change from "params" to "attributes"

- Change from "values" to "defaults"

- get rid of IsServerMatch

- need a way for route to specify what methods to use for matching, so that
  extended objects don't need to hook in to the matcher