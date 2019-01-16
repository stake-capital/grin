# grin
Everything related to Grin

# Install Grin

## Upgrade the system
```
sudo apt update
sudo apt upgrade -y
sudo apt install gcc git make -y
```
Attention, only gcc-6 is supported on cuda. 

```
sudo apt-get install gcc-6 g++-6 -y && \
sudo update-alternatives --install /usr/bin/gcc gcc /usr/bin/gcc-6 60 --slave /usr/bin/g++ g++ /usr/bin/g++-6
```

## Install packages
```
sudo apt install cmake git libgit2-dev clang libncurses5-dev libncursesw5-dev zlib1g-dev pkg-config libssl-dev llvm cargo
```
## Install Rust 
```
curl https://sh.rustup.rs -sSf | sh; source $HOME/.cargo/env)
```

## How to mine
https://github.com/mimblewimble/docs/wiki/How-to-mine-Grin
