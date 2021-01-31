# asdf-go-repos-sync
Plugin for [asdf](https://github.com/asdf-vm/asdf) Package Manager, install [taskfile.dev](https://taskfile.dev/#/).

## Install

Look for the Latest Release of [go-task/task](https://github.com/go-task/task/releases).

```sh
asdf plugin-add task https://github.com/nolte/asdf-task.git

asdf install task 3.2.2
```

## Development


Direct call, for local development.
```sh
ASDF_INSTALL_TYPE=test \
  ASDF_INSTALL_VERSION=3.2.1 \
  ASDF_INSTALL_PATH=/tmp/plugin \
  ./bin/install
```
