<p align="left">
  <picture>
    <source media="(prefers-color-scheme: dark)"  srcset="https://radprogrammer.com/assets/radFormatter/radformatter-logo-reversed.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://radprogrammer.com/assets/radFormatter/radformatter-logo.svg">
    <img alt="radFormatter Logo" src="assets/radlexer-logo.svg" width="420">
  </picture>
</p>

radFormatter is a CST-aware Delphi source code formatter for teams that want
consistent formatting without rewriting code by hand.

This public repository is used for release distribution, issue tracking, and public project information.

## Status

radFormatter is preparing for alpha testing.

Public downloads will be published on the [GitHub Releases](https://github.com/radprogrammer/radFormatter/releases) page when alpha builds are available. Product documentation lives on [radprogrammer.com](https://radprogrammer.com/radFormatter/).

## What It Does

- Formats Delphi source while preserving program behavior
- Supports both a command-line formatter and a RAD Studio IDE plugin
- Works with configurable formatting profiles
- Supports CI workflows with check and diff modes
- Targets Delphi source files such as `.pas`, `.dpr`, `.dpk`, `.dpkw`, and `.inc`

## Documentation

- [Product overview](https://radprogrammer.com/radFormatter/)
- [Command-line usage](https://radprogrammer.com/radFormatter/docs/radFormatter-cli.html)
- [Configuration options](https://radprogrammer.com/radFormatter/docs/config-options.html)
- [Built-in profiles](https://radprogrammer.com/radFormatter/docs/profiles.html)
- [Known limitations](https://radprogrammer.com/radFormatter/docs/known-limitations.html)
- [IDE plugin](https://radprogrammer.com/radFormatter/ide.html)

## Reporting Issues

GitHub issues are the right place for alpha feedback about formatting behavior,
crashes, idempotence problems, unclear documentation, and workflow friction.

For formatting issues, include:

- radFormatter version
- Whether you used the CLI or IDE plugin
- Delphi / RAD Studio version
- Profile and config file used, if any
- Input snippet
- Actual formatted output
- Expected formatted output
- Whether formatting the output a second time changes it again
- Any conditional compilation symbols or include paths needed to reproduce it

Only share code that you are allowed to publish. If the original source is
proprietary, reduce the report to a minimal synthetic snippet that still
reproduces the problem.

## Support Scope

This repository is for public product feedback and release tracking. Purchase,
license, and account support channels will be documented separately as the alpha
and commercial launch process comes online.