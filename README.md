# observeinc/homebrew-tap (retired)

This tap is no longer maintained. The `observe-agent` formula is disabled and `brew install` refuses to install it. It only ever offered observe-agent v0.1.10, a 2024 build.

Install the Observe Agent with the supported installers instead: https://docs.observeinc.com/docs/install-on-a-host

If you installed `observe-agent` from this tap, remove it and the tap, then reinstall with a supported installer:

```sh
brew uninstall observe-agent
brew untap observeinc/tap
```
