# std
The standard library for the Quill programming language.

This package implements functionality shared across every target backend, meaning you should never include this package as a dependency directly (unless you are writing a library with `"backend": "any"`). Instead include a backend-specific implementation, such as `std-c` for `"backend": "c"`.