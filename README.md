# GITOPS PLATFORM CONFIGURATION 

[![Build status](https://github.com/kriipke/demo-gitops)](https://github.com/boolpurist/week_calendar_cli/actions)

## PURPOSE OF REPO 

## USAGE


### 1. Acquire `vendir` 

For more inforamtion about Vendir, see here:

https://github.com/carvel-dev/vendir

```sh
VERSION=0.43.0

curl -LO https://github.com/carvel-dev/vendir/releases/download/v$VERSION/vendir-linux-$ARCH
chmod a+x vendir-linux-$ARCH && sudo install vendir-linux-$ARCH /usr/local/bin/vendir
```

### 2. Clone this Repository


This site is accessible at https://github.com/kriipke/???

```sh
git clone https://github.com/kriipke/demo-gitops -b main 
cd demo-gitops 
vendir sync
```

```
Output:

```text
+-------------+------------+------------+
| Week Number | From       | To         |
+-------------+------------+------------+
| 26          | 2023-06-26 | 2023-07-02 |
+-------------+------------+------------+
```

More examples for usage can be found here [here](./Examples.md).

## Current version

Current version is 0.1.3

Version on crates.io and the last git [tag](https://github.com/BoolPurist/week_calendar_cli/releases/tag/v0.1.3) 
correspond to the current version. 

## How to install it

### Install from crates.io

This appliaction is also published on this [page](https://crates.io/crates/week_calendar) of crates.io 

You can install via 
```sh
cargo install week_calendar
```

### Install it from source

1. Clone this repository
2. Go into to the cloned folder
3. Type the following command into the terminal

```sh
cargo install --path=. --force
```

## Changelog 

Changelog can be found [here](./CHANGELOG.md)

## Licenses

This appliaction can be used under MIT or Apache 2.0 at your choice
