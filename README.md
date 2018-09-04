# Introduction

**A**(rch)**L**(inux)**I**(nstall)**S**(cript) is a very minimal script that makes my installations of Arch Linux on my various machines as painless and fast as possible. It goes from blank to ready to go in a matter of minutes. Bonus point, everything is automated. 

This script currently supports installs on:
- EUFI systems
- Non-EUFI systems
- External storage

**NOTE:** This script only supports basic hardware with Intel inside. If you need to, you'll have to install additional drivers yourself. (wifi, bluetooth, ...)

# How to use ? 

Recommended:

```bash
wget https://github.com/gawlk/alis/blob/master/fifo.sh
chmod +x fifo.sh
# Review the code and check that everything is up to date according to the "Installation guide"
./fifo.sh
```

Not recommended:

```bash
curl -sSL https://git.io/fAlOi | bash
```
