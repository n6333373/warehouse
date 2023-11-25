## Sublime Self Patcher

This is a Sublime Text 4 plugin which can patch Sublime Text itself (and Sublime Merge).

## Supported Environments

- Linux x64
- Windows x32
- Windows x64

There is no other platform or architecture supported because I don't use them.

## Installation

First, you have to find out the `Packages` directory.

- If you are using a portable version of Sublime Text, it is `Data/Packages`.
- If you are using a installed version of Sublime Text,
  - On Windows, it is `%appdata%\Sublime Text\Packages`
  - On Linux, it is `$HOME/.config/sublime_text/Packages`

Now, decompress `SelfPatcher.zip` into the `Packages` directory
so that the directory structure looks like the following:

```text
Packages/
└── SelfPatcher
    ├── boot.py
    ├── ...
```

## Usage

### Patch Self

- If you are using a unregistered dev build, this plugin should show a popup for patching when starting.
- If you are using a stable build, you can patch from the menu: `Help ⇒ Patch This Application`

### Patch External Sublime Text/Merge

Click the menu: `Help ⇒ Patch External Sublime Text/Merge` and then select the executable of Sublime Text/Merge.

## This Plugin is Suspicious

Then do it by your own hands. https://gist.github.com/maboloshi/feaa63c35f4c2baab24c9aaf9b3f4e47
