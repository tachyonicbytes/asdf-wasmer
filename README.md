<div align="center">

# asdf-wasmer [![Build](https://github.com/tachyonicbytes/asdf-wasmer/actions/workflows/build.yml/badge.svg)](https://github.com/tachyonicbytes/asdf-wasmer/actions/workflows/build.yml) [![Lint](https://github.com/tachyonicbytes/asdf-wasmer/actions/workflows/lint.yml/badge.svg)](https://github.com/tachyonicbytes/asdf-wasmer/actions/workflows/lint.yml)


[wasmer](https://docs.wasmer.io/) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add wasmer
# or
asdf plugin add wasmer https://github.com/tachyonicbytes/asdf-wasmer.git
```

wasmer:

```shell
# Show all installable versions
asdf list-all wasmer

# Install specific version
asdf install wasmer latest

# Set a version globally (on your ~/.tool-versions file)
asdf global wasmer latest

# Now wasmer commands are available
wasmer --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/tachyonicbytes/asdf-wasmer/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [TachyonicBytes](https://github.com/tachyonicbytes/)
