<div align="center">

# asdf-hypershift [![Build](https://github.com/mrWinston/asdf-hypershift/actions/workflows/build.yml/badge.svg)](https://github.com/mrWinston/asdf-hypershift/actions/workflows/build.yml) [![Lint](https://github.com/mrWinston/asdf-hypershift/actions/workflows/lint.yml/badge.svg)](https://github.com/mrWinston/asdf-hypershift/actions/workflows/lint.yml)

[hypershift](https://github.com/openshift/hypershift) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`
- `make` and `golang >= 1.19`

# Install

Plugin:

```shell
asdf plugin add hypershift https://github.com/mrWinston/asdf-hypershift.git
```

hypershift:

```shell
# Show all installable versions
asdf list-all hypershift

# Install specific version
asdf install hypershift latest

# Set a version globally (on your ~/.tool-versions file)
asdf global hypershift latest

# Now hypershift commands are available
hypershift version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/mrWinston/asdf-hypershift/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Marius Schulz](https://github.com/mrWinston/)
