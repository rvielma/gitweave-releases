# GitWeave releases

Prebuilt binaries of `gw`, the GitWeave command line.

## Install

With Homebrew (macOS and Linux):

```sh
brew install rvielma/tap/gitweave
```

Or download the archive for your platform from the
[latest release](https://github.com/rvielma/gitweave-releases/releases/latest),
extract it and put `gw` (`gw.exe` on Windows) on your `PATH`:

| Platform | Archive |
|---|---|
| macOS, Apple Silicon | `gitweave-vX.Y.Z-aarch64-apple-darwin.tar.gz` |
| macOS, Intel | `gitweave-vX.Y.Z-x86_64-apple-darwin.tar.gz` |
| Linux, x86_64 (static) | `gitweave-vX.Y.Z-x86_64-unknown-linux-musl.tar.gz` |
| Windows, x64 (also Windows on ARM) | `gitweave-vX.Y.Z-x86_64-pc-windows-gnu.zip` |

Each release lists the SHA-256 of every archive in `SHA256SUMS`.

```sh
gw --version
```
