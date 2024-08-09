# nixos-pythonenv

This repository contains everything required to set up a complete Python environment using Nix Flakes & Nix Shell.

The Nix Shell definition is included in the Nix Flake definition.

The Nix Flake is onfigured to open the Nix Shell using `zsh`, however, any shell can be used.

## Editing the Nix Flake
Packages and the default shell can be modified directly using the `flake.nix` file.

## Executing the environment
In order to execute the environment from any shell, run the following:

```Bash
nix develop
```
The shell will be created with the packages defined on `flake.nix`.
