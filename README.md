Prerequirements:   
Install oh-my-zsh:   
```
cd
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

refer to this link:   
https://github.com/ohmyzsh/ohmyzsh   

```
mkdir ~/Package
cd Package
git clone https://github.com/yuzukicat/oh-my-zsh-conf.git
git clone https://github.com/ChesterYue/ohmyzsh-theme-passion.git
git clone https://github.com/zsh-users/zsh-autosuggestions.git
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git
sudo cp -R Package/oh-my-zsh-conf/.zshrc ~/
sudo cp -R Package/ohmyzsh-theme-passion/passion.zsh-theme ~/.oh-my-zsh/custom/themes
sudo cp -R Package/zsh-autosuggestions ~/.oh-my-zsh/custom/plugins
sudo cp -R Package/zsh-syntax-highlighting ~/.oh-my-zsh/custom/plugins
```

refer to this link:   
https://gist.github.com/yovko   

```
nano ~/.tmux.conf
mkdir ~/.tmux
sudo cp -R Package/nord-tmux ~/.tmux
tmux source-file ~/.tmux.conf
exit
exit
```
nano ~/.tmux.conf   

```
# Set default shell
set -g default-shell /bin/zsh

# Run nord.tmux
run-shell "~/.tmux/nord-tmux/nord.tmux"
```

refer to this link:   
https://github.com/arcticicestudio/nord-tmux   

Thanks to adamwuqwq, the macos(apple m1/m2) solution:   
refer to this link:   
https://github.com/adamwuqwq/my_shell_config   
