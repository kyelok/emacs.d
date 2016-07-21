# emacs.d

W. Nicholas Greene's emacs configuration. Checkout this repo to your home directory
(including submodules) as `.emacs.d` and launch emacs. It should grab
the required packages from the package manager:

```
cd
git clone git@github.com:wngreene/emacs.d.git .emacs.d
cd .emacs.d
git submodule update --init Highlight-Indentation-for-Emacs
emacs . &
```

### Requires:
- emacs24
- cpplint.py
- pylint
- languagetool
