<div align="center">

# asdf-process-compose [![Build](https://github.com/martino/asdf-process-compose/actions/workflows/build.yml/badge.svg)](https://github.com/martino/asdf-process-compose/actions/workflows/build.yml) [![Lint](https://github.com/martino/asdf-process-compose/actions/workflows/lint.yml/badge.svg)](https://github.com/martino/asdf-process-compose/actions/workflows/lint.yml)

[process-compose](https://github.com/F1bonacc1/process-compose) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add process-compose
# or
asdf plugin add process-compose https://github.com/martino/asdf-process-compose.git
```

process-compose:

```shell
# Show all installable versions
asdf list-all process-compose

# Install specific version
asdf install process-compose latest

# Set a version globally (on your ~/.tool-versions file)
asdf global process-compose latest

# Now process-compose commands are available
process-compose version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/martino/asdf-process-compose/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Martino Pizzol](https://github.com/martino/)
