
# Bootstrapping the Environment

You should have `asdf` and a `direnv` compatible environment loader
enabled (e.g. `quickenv`).

Then everything should be bootstrappable from there.

To bootstrap you can run:

```sh
asdf plugin add python
asdf plugin add nodejs
asdf plugin add rust

asdf isntall
```

Then the toolchains should install.

## Direnv

```sh
direnv allow
```

## Quickenv: TODO

```sh
quickenv reload
```

# TODO

- [asdf-plugin-manager](https://github.com/asdf-community/asdf-plugin-manager)
- example of ad hoc installation of tools into a local `.bin` folder and add to `PATH`
