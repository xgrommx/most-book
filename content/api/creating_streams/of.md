## [`of :: a → Stream a` | `just :: a → Stream a`](https://github.com/cujojs/most/blob/master/lib/source/core.js#L19-L21)

Returns an stream that contains a constant element with a type `a`.

#### Arguments
  * `(a)` : A constant to be emitted by the resulting stream.

#### Returns
  * `(Stream)` : A stream that will emit the specified constant and then terminate.

#### Notation <sup>[*]()</sup>
  * `most.of(x): x|`

#### `Example`

[](http://jsbin.com/gonogug/embed?js,console)