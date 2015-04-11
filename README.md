# Submodule
This repository uses a submodule to pull in reveal.js, so after cloning you still need to pull in the submodule. If you don't do this the presentation will not have any layout.

```bash
git submodule update --init
```


# Reveal.js template

This is a very simple repository which can be used to start a new reveal.js
presentation.
To keep everything clean it puts the actual reveal.js files in a subdirectory
(reveal/) which is a git submodule. This allows for easy updating of reveal.js
and doesn't mix your own files with the reveal files.

## Known problems
There is currently one known problem with this setup: it breaks the sidenotes,
as the sidenotes html file is not where reveal.js expects it to be.

%% vim: textwidth=80 wrap
