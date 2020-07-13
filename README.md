atoi
=====

> `atoi(3)` bindings for ZZ

## Installation

Add this to your `zz.toml` file:

```toml
[dependencies]
atoi = "*"

[repos]
atoi = "git://github.com/zzmodules/atoi"
```

## Usage

```c++
using atoi::{
  atoi, atol, atoll
}
```

## API

`atoi(str)` and the following `atoi` like functions are exported:

* `atol(str)`
* `atoll(str)`

## License

MIT
