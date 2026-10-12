# Create your own Sui binary
- 1 Check the environment and CPU

```
uname -a
lscpu
```
- 2
```
sudo apt update
sudo apt install -y build-essential clang cmake pkg-config libssl-dev \
libclang-dev git curl unzip
```
- 3
```
rustc --version
cargo --version
```
- 4 Clone the sui repository
```
https://github.com/MystenLabs/sui
```
- 5 Compile sui from the cloned repository
```
cargo build --release
```
# Using your own Sui binary
* Move your Sui binary to `builder-scaffold/docker/` folder
