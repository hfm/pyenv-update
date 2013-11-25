# pyenv-update

This [pyenv](https://github.com/yyuu/pyenv) plugin, is a port of the [rbenv-update](https://github.com/rkh/rbenv-update), adds the `pyenv update` command than updated pyenv and all installed plugins.

## Installation

```sh
mkdir -p $PYENV_ROOT/plugins
git clone git@github.com:Tacahilo/pyenv-update.git $PYENV_ROOT/plugins/pyenv-update
```

## Usage

```
$ pyenv update
updating pyenv
 |  Already on 'master'
 |  From git://github.com/yyuu/pyenv
 |  5e20237..bc2d245  master     -> origin/master
 |  * [new branch]      add-pyparallel -> origin/add-pyparallel
 |  From git://github.com/yyuu/pyenv
 |  * branch            master     -> FETCH_HEAD
 |  Updating 5e20237..bc2d245
 |  Fast-forward
 |  README.md                                          |  2 +
 |  plugins/python-build/share/python-build/2.4        |  4 +-
 |  plugins/python-build/share/python-build/2.4.1      |  4 +-
 ... snip ...
 |  rename plugins/python-build/share/python-build/{3.3.3-rc2 => 3.4.0b1} (53%)
 |  delete mode 100644 plugins/python-build/share/python-build/patches/2.6-dev/Python-2.6-dev/001_openssl_no_ssl2.patch

updating pyenv-update
 |  Already on 'master'
 |  From github.com:Tacahilo/pyenv-update
 |  * branch            master     -> FETCH_HEAD
 |  Already up-to-date.
```

## AUTHOR

Takahiro OKUMURA hfm.garden@gmail.com

## LICENSE

See [the document](./LICENSE).
