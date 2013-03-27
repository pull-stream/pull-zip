# pull-zip

zip [pull-stream](https://github.com/dominictarr/pull-stream)

combine N streams into N length tuples.

## Example

``` js
var pull = require('pull')
var zip  = require('pull-zip')

zip(pull.values([1, 2, 3]), pull.values(['A', 'B', 'C']))
.pipe(pull.log())
```

## License

MIT
