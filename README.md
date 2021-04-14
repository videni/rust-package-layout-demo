
 cargo run 
```
   Compiling hallo v0.1.0 (/Users/vidy/www/rust-package-layout-demo)
error[E0432]: unresolved import `hallo::bar::bar`
 --> src/main.rs:3:5
  |
3 | use hallo::bar::bar;
  |     ^^^^^^^^^^^^^^^ no `bar` in `bar`

error: aborting due to previous error

For more information about this error, try `rustc --explain E0432`.
error: could not compile `hallo`

To learn more, run the command again with --verbose.
```