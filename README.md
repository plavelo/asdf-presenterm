<div align="center">

# asdf-presenterm [![Build](https://github.com/plavelo/asdf-presenterm/actions/workflows/build.yml/badge.svg)](https://github.com/plavelo/asdf-presenterm/actions/workflows/build.yml) [![Lint](https://github.com/plavelo/asdf-presenterm/actions/workflows/lint.yml/badge.svg)](https://github.com/plavelo/asdf-presenterm/actions/workflows/lint.yml)

[presenterm](https://github.com/mfontanini/presenterm) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).

# Install

Plugin:

```shell
asdf plugin add presenterm
# or
asdf plugin add presenterm https://github.com/plavelo/asdf-presenterm.git
```

presenterm:

```shell
# Show all installable versions
asdf list-all presenterm

# Install specific version
asdf install presenterm latest

# Set a version globally (on your ~/.tool-versions file)
asdf global presenterm latest

# Now presenterm commands are available
presenterm --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/plavelo/asdf-presenterm/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [plavelo](https://github.com/plavelo/)
