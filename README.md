# config

Some useful configurations in this repository.

```bash
sudo apt-get install zsh
sh -c "$(wget https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh -O -)"

wget https://raw.githubusercontent.com/caiogondim/bullet-train-oh-my-zsh-theme/master/bullet-train.zsh-theme
mv bullet-train.zsh-theme .oh-my-zsh/themes

wget https://raw.githubusercontent.com/sabirribas/config/master/tmux.conf -O .tmux.conf
wget https://raw.githubusercontent.com/sabirribas/config/master/vimrc -O .vimrc
wget https://raw.githubusercontent.com/sabirribas/config/master/zshrc -O .zshrc
```

```bash
conda install -c conda-forge jupyter_contrib_nbextensions

jupyter contrib nbextension install --user
jupyter nbextension enable toc2/main
jupyter nbextension enable codefolding/main
jupyter nbextension enable execute_time/ExecuteTime
jupyter nbextension enable collapsible_headings/main
jupyter nbextension enable contrib_nbextensions_help_item/main
jupyter nbextension enable nbextensions_configurator/tree_tab/main
jupyter nbextension enable nbextensions_configurator/config_menu/main
```
