# festart.nvim

`festart.nvim` is a pre-configured neovim setup designed specifically for frontend development, aimed at helping you quickly get started on your neovim frontend development journey. 

This project is a single-file setup.

The inspiration for `festart.nvim`, as well as many of its configurations, were taken from the [kickstart.nvim](https://github.com/nvim-lua/kickstart.nvim) project and the configurations provided by [craftzdog](https://github.com/craftzdog/dotfiles-public). I am very grateful to them, as I have learned a lot from them.

### Installation

This requires Neovim version >= 0.8.

- Backup your previous configuration
- Fork the repository so you can make changes as necessary
- Copy and paste the `init.lua` file from `festart.nvim` into `$HOME/.config/nvim/init.lua`
- Open the `init.lua` file in nvim, and start installation, Ignore any error messages.
- Restart Neovim
- Manually install `prettierd` using `Mason` to enable formatting.

Please refer to the installation video:

https://user-images.githubusercontent.com/22109673/230092791-593164f4-7b59-4de8-8db0-66dca44a1f81.mov


### Contribution
Contributions to festart.nvim are welcome! To contribute, please fork the repository and create a pull request.


### License
`festart.nvim` is released under the MIT License. For more information, please refer to the LICENSE file.

### FAQ

- Q: What if I had previous neovim configurations?
- A: If you had previous neovim configurations, it is recommended that you backup your configuration information and then delete it with `rm -rf ~/.local/share/nvim/`. use the `init.lua` file from `festart.nvim` to replace your old configuration.