# my_rust
rust practice

# Setup rust ubuntu 14.04

curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh

# check version
rustc --version

# get started
vim helloWorld.rs 

# add this line
# program to print hello world
fn main() {
    println!("Hello, world!");
}

# compile the program
rustc helloWorld.rs

# running the program
./helloWorld



