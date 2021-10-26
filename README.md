<div align="center">

# asdf-semver [![Build](https://github.com/mathew-fleisch/asdf-semver/actions/workflows/build.yml/badge.svg)](https://github.com/mathew-fleisch/asdf-semver/actions/workflows/build.yml) [![Lint](https://github.com/mathew-fleisch/asdf-semver/actions/workflows/lint.yml/badge.svg)](https://github.com/mathew-fleisch/asdf-semver/actions/workflows/lint.yml)


[semver](https://github.com/fsaintjacques/semver-tool) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`: generic POSIX utilities.

# Install

Plugin:

```shell
asdf plugin add semver
# or
asdf plugin add semver https://github.com/mathew-fleisch/asdf-semver.git
```

semver:

```shell
# Show all installable versions
asdf list-all semver

# Install specific version
asdf install semver latest

# Set a version globally (on your ~/.tool-versions file)
asdf global semver latest

# Now semver commands are available
semver --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/mathew-fleisch/asdf-semver/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Mathew Fleisch](https://github.com/mathew-fleisch/)
