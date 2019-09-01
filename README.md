# Rust cheat-sheet

## Tools:
* `cargo` - Build system and packet manager
* `rustc` - Rust compiler
* `rustup` - Installs The Rust Programming Language from the official release channels
* `rustfmt` - Autoformatter 

## Creating a new project: 
`cargo new <project name>` - Creates a project structure. Auto setup of git and gitignore is awesome. 

## Building / Running:
`cargo build` - Creates an executeable in `target/debug` directory.
`cargo check` - Will test is the code compiles or not. Way faster than the build command.
`cargo build --release` - Will create an optimized executeable in `target/release` directory.
`cargo run` - Will create an excuteable and run it.
`cargo dock --open` - Will create build documentation for all dependencies and open it in browser.
