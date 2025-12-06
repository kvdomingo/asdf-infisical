<div align="center">

# asdf-infisical [![Build](https://github.com/kvdomingo/asdf-infisical/actions/workflows/build.yml/badge.svg)](https://github.com/kvdomingo/asdf-infisical/actions/workflows/build.yml) [![Lint](https://github.com/kvdomingo/asdf-infisical/actions/workflows/lint.yml/badge.svg)](https://github.com/kvdomingo/asdf-infisical/actions/workflows/lint.yml)

[infisical](https://github.com/Infisical/infisical) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

**TODO: adapt this section**

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add infisical
# or
asdf plugin add infisical https://github.com/kvdomingo/asdf-infisical.git
```

infisical:

```shell
# Show all installable versions
asdf list-all infisical

# Install specific version
asdf install infisical latest

# Set a version globally (on your ~/.tool-versions file)
asdf global infisical latest

# Now infisical commands are available
infisical --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/kvdomingo/asdf-infisical/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Kenneth V. Domingo](https://github.com/kvdomingo/)
