PourOver Example
===

This is an example implementation using different [PourOver](http://nytimes.github.io/pourover/) filters to select articles. It features:

* Multiple `inclusionFilter`s for filtering by checkbox across multiple categories
* A date range picker using a `continuousRangeFilter` and [Pikaday](https://github.com/dbushell/Pikaday) for the UI. Note: This uses a [Pikaday fork](https://github.com/newslynx/Pikaday) to take advantage of `clearDate` and `onClear` functionality. Follow that PR [here](https://github.com/dbushell/Pikaday/pull/134).
* Text search across headlines using Bloudhound for fast string matching which hands off to a `manualFilter` as theoretically discussed [here](https://github.com/NYTimes/pourover/issues/17).

#### [Demo](http://newslynx.github.io/pourover-example)

License MIT