# Rust

## install Rust
install Rust by `rustup` which management Rust version.

### install rustup to mac
```
curl https://sh.rustup.rs -sSf | sh
```
confirm success
```
rustc --version
rustup update
```
### local doc on browser
```
rustup doc
```
----------------
## hello world
### file name
```
touch main.rs
```
### write
```rust
fn main() {
    // 世界よ、こんにちは
    println!("Hello, world!");
}
```

### execute
#### compile
rustc main.rs
#### go!!!!!!
./main

-----------------
## ref
https://doc.rust-jp.rs/book/second-edition/ch01-00-getting-started.html

### doc