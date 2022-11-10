# Hello Rust

Simple Rust app which shows how to debug a Rust program in Visual Studio Code

## Initial Setup for Rust Debugging in VS Code

1. Install 'rust-analyzer' VS Code Extension
2. Install 'CodeLLDB' VS Code Extension (for MacOS) or 'Microsoft C++' VS Code Extension for Windows

## Enabling Debug in a Rust Project 
1. Run 'cargo new <project_name>' from Terminal to create new Rust Project
2. Run 'code <project_name>' from Terminal to open that project in VS Code
3. Click on Run & Debug tab in VS Code
4. Click on "Show all automatic debug configurations"
5. Click on "Add configuration" in dropdown.
6. Choose 'LLDB'
7. Click 'Yes' on the dialog box that pops up.
8. This will generate a new '.vscode/launch.json' file which will allow debugging.
9. Set any breakpoints you need in the source.
10. Go to the Run & Debug tab on VS Code.
11. Click the Green arrow on the top to start running.

# Links

* [Rust Language Website](https://www.rust-lang.org)
* [The Rust Programming Language Book](https://doc.rust-lang.org/book/)
* [The Cargo Book](https://doc.rust-lang.org/stable/cargo/)
* [Instructions for setting up in VS Code](https://code.visualstudio.com/docs/languages/rust)
