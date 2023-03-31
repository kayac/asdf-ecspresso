<div align="center">

# asdf-ecspresso [![Build](https://github.com/kayac/asdf-ecspresso/actions/workflows/build.yml/badge.svg)](https://github.com/kayac/asdf-ecspresso/actions/workflows/build.yml) [![Lint](https://github.com/kayac/asdf-ecspresso/actions/workflows/lint.yml/badge.svg)](https://github.com/kayac/asdf-ecspresso/actions/workflows/lint.yml)


[ecspresso](https://github.com/kayac/ecspresso) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

**TODO: adapt this section**

- `bash`, `curl`, `tar`: generic POSIX utilities.
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add ecspresso
# or
asdf plugin add ecspresso https://github.com/kayac/asdf-ecspresso.git
```

ecspresso:

```shell
# Show all installable versions
asdf list-all ecspresso

# Install specific version
asdf install ecspresso latest

# Set a version globally (on your ~/.tool-versions file)
asdf global ecspresso latest

# Now ecspresso commands are available
ecspresso version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/kayac/asdf-ecspresso/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [KAYAC Inc.](https://github.com/kayac/)
