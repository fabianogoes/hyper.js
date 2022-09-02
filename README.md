![Hyper.js](./hyper.js.png)
# Hyper.js
[Hyper.js Official site](https://hyper.is)

My hyper.js configurations

## ZSH

```bash
brew install zsh
chsh -s /bin/zsh
```

## Oh My Zsh

→ [https://ohmyz.sh](https://ohmyz.sh/)

→ [Install](https://ohmyz.sh/#install)

```bash
sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

→ Configurando zsh-syntax-highlighting, zsh-autosuggestions, zsh-completions

```bash
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git $ZSH_CUSTOM/plugins/zsh-syntax-highlighting
git clone https://github.com/zsh-users/zsh-autosuggestions $ZSH_CUSTOM/plugins/zsh-autosuggestions
git clone https://github.com/zsh-users/zsh-completions.git $ZSH_CUSTOM/plugins/zsh-completions
```

→ `~/.zshrc`

```bash

source $ZSH_CUSTOM/plugins/zsh-autosuggestions/zsh-autosuggestions.zsh
source $ZSH_CUSTOM/plugins/zsh-syntax-highlighting/zsh-syntax-highlighting.zsh
source $ZSH_CUSTOM/plugins/zsh-completions/zsh-completions.plugin.zsh
```

## Customize Hyper

`~/.hyper.js`

→ **Plugins**

[https://github.com/bnb/awesome-hyper](https://github.com/bnb/awesome-hyper)

```jsx
plugins: [
        "hypertheme",
        "hyper-omni-theme",
        "hyper-opacity",
        "hypercwd",
        "hyper-active-tab",
        "hyperborder",
        "hyper-hide-title",
        "hyperterm-paste",
        "hyperline"
    ]
```

→ **Font**

[MesloLGS NF Bold Italic.ttf](./MesloLGS_NF_Bold_Italic.ttf)

[MesloLGS NF Bold.ttf](./MesloLGS_NF_Bold.ttf)

[MesloLGS NF Italic.ttf](./MesloLGS_NF_Italic.ttf)

[MesloLGS NF Regular.ttf](./MesloLGS_NF_Regular.ttf)

```jsx
fontFamily: '"MesloLGS NF"',
```

→ **Opacity**

[GitHub - lucleray/hyper-opacity: Set the opacity of your Hyper terminal (Windows and MacOS)](https://github.com/lucleray/hyper-opacity)

```jsx
module.exports = {
  config: {
    opacity: 1.00
  }
}
```

## Themes

- ****Omni for [Hyper](https://www.npmjs.com/package/hyper-omni-theme)**
    
```bash
hyper install hyper-omni-theme
```
    

## Optional

### [Fig](https://fig.io/)

```bash
brew install fig
fig
```

## Shortcut

`Shift` + `Command` + `F5` = Full Realod

`Shift` + `Command` + `R` = Realod

## File configuration

[]()

## References

- https://github.com/ohmyzsh/ohmyzsh
- https://github.com/zsh-users/zsh-syntax-highlighting
- https://github.com/zsh-users/zsh-autosuggestions
- https://github.com/zsh-users/zsh-completions
- https://github.com/romkatv/powerlevel10k
