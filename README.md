# homebrew-murl

Homebrew tap for [mURL](https://github.com/thatwasyahya/mURL) — one
identifier that opens a whole working context.

```bash
brew tap thatwasyahya/murl
brew install murl
```

On Linux and macOS this installs both `murl` and `murl-daemon`. The daemon
provides the consent dialog; on macOS it is required for activation to work
at all, because a Launch Services activation has no controlling terminal:

```bash
murl-daemon service install
```

mURL is **experimental**. The formula is generated from
[`packaging/homebrew/murl.rb`](https://github.com/thatwasyahya/mURL/blob/main/packaging/homebrew/murl.rb)
in the main repository — send changes there, not here.
