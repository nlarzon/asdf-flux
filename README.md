<div align="center">

# asdf-flux ![Build](https://github.com/nlarzon/asdf-flux/workflows/Build/badge.svg) ![Lint](https://github.com/nlarzon/asdf-flux/workflows/Lint/badge.svg)

[flux](https://fluxcd.io) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Why?](#why)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add flux
# or
asdf plugin add https://github.com/nlarzon/asdf-flux.git
```

flux:

```shell
# Show all installable versions
asdf list-all flux

# Install specific version
asdf install flux latest

# Set a version globally (on your ~/.tool-versions file)
asdf global flux latest

# Now flux commands are available
flux --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/nlarzon/asdf-flux/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Niklas Larsson](https://github.com/nlarzon/)
