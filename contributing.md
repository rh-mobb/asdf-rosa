# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

#
asdf plugin test rosa https://github.com/rh-mobb/asdf-rosa.git "rosa version"
```

Tests are automatically run in GitHub Actions on push and PR.
