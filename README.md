My Neovim Setup
===============
> [!TIP]
> Turn your terminal into a full-fledged integrated development environment (IDE) using [Neovim](https://neovim.io/)

<div align="center">
    <a href="https://gyazo.com/57ccdc67266ee53eb6911a3a9b75be58"><img id="screenshot" alt="Neovim in action!" src="https://i.gyazo.com/57ccdc67266ee53eb6911a3a9b75be58.gif" width="750"/></a>
</div>

Install Neovim
--------------
### Linux / Mac
- `brew install neovim`
- `spack install neovim`
### Windows
- `scoop install neovim`
- `choco install neovim`
- `winget install Neovim.Neovim`

Configure Neovim
----------------
### Linux / Mac
```shell
git clone https://github.com/jhwohlgemuth/my-neovim-setup.git "${HOME}/.config/nvim/"
```

### Windows
```shell
git clone https://github.com/jhwohlgemuth/my-neovim-setup.git
cd my-neovim-setup
./Invoke-Setup.ps1
```