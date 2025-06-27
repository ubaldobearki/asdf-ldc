# asdf-ldc [![Build Status](https://travis-ci.org/sylph01/asdf-dmd.svg?branch=master)](https://travis-ci.org/sylph01/asdf-dmd)

[LDC](https://github.com/ldc-developers/ldc), the LLVM D Compiler plugin for the [asdf](https://github.com/asdf-vm/asdf) version manager

## Install

```
asdf plugin add ldc https://github.com/ubaldobearki/asdf-ldc.git
```

## Use
```shell
#show recent releases
asdf list all ldc

#install specific version
asdf install ldc 1.40.1

#check ldc command (make sure to setup your ~/.tool-versions)
ldc2 --version
```

