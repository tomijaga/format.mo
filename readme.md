# Format.mo
A text formatter for motoko

```
    F.format("Hello, {}!", [#text("World")])  // -> Hello, World!
    F.format("{} * {} = {}", 
        [#num(2), #num(2), #num(4)])          // -> 2 * 2 = 4
    F.format("array: {}", 
        [#numArray([1, 1, 2])])               // -> array: [1, 1, 2]
```

## Variant Types

`#num` - Nat or Int

`#numArray` - Nat or Int array

`#natArrayMut` - Mutable Nat array

`#intArrayMut` - Mutable Int array


`#char` - Char  

`#charArray` - Char array

`#charArrayMut` - Mutable Char array


`#text` - Text

`#textArray` - Text array

`#textArrayMut` - Mutable Text array
