# ConsHomfold Program, which Predicts RNA Single Secondary Structures to Consider Sparse RNA Structural Alignments
# Installation
This project has been written in mainly Rust, a systems programming language.
So first, you need to install the Rust compiler, package manager, and standard library. 
Visit [the Rust website](https://www.rust-lang.org) to see more about this language.
You can install these 3 components with 1 line as follows:
```bash
$ curl https://sh.rustup.rs -sSf | sh
```
The above installation is done by [Rustup](https://github.com/rust-lang-nursery/rustup.rs), so you can easily switch a compiler to use. 
Now you can install the ConsHomfold program as follows: 
```bash
$ cargo install conshomfold
```
Check if this program has been installed properly as follows:
```bash
$ conshomfold # Its available command options will be displayed.
```
After the test, the figures shown in the paper of the ConsHomfold program can be reproduced:
```bash
$ cd src
$ ./run_all.py # Install python packages required to the reproduction. Saved figures will appear at the "../assets/images" directory.
```

# Author
[Heartsh](https://github.com/heartsh)

# License
Copyright (c) 2018 Heartsh  
Licensed under [the MIT license](http://opensource.org/licenses/MIT).
