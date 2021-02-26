# stacc-CLI

This repository is being used to hold Stacc CLI [releases](https://github.com/stacc/stacc-CLI/releases)

## Installation

* [Snap](#using-snap-linux)
* [Homebrew](#using-homebrew-macos--linux)
* [From terminal](#from-terminal)
* [Direct download](#direct-download)

### Using snap (Linux)

Simply run the following command

```
$ snap install stacc
```

### Using homebrew (MacOS / Linux)

First add the repository with

```
$ brew tap stacc/stacc-cli
```

Then install the CLI with

```
$ brew install stacc
```

### From terminal

MacOS and Linux users

```
$ curl -s https://raw.githubusercontent.com/stacc/stacc-CLI/main/install.sh | bash -s --
```

Windows users

```
$ curl -LSs https://raw.githubusercontent.com/stacc/stacc-CLI/main/install.bat -o %TEMP%\stacc-install.bat && CMD /C %TEMP%\stacc-install.bat && del %TEMP%\stacc-install.bat
```

### Direct download

Download the latest release [here](https://github.com/stacc/stacc-CLI/releases/latest)
