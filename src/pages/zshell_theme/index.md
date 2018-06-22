---
path: '/oh-my-zsh-custom-theme'
title: 'OhMyZsh theme'
date: 2018-06-22
---

```bash
PROMPT=' %{$fg[cyan]%}%c $(git_prompt_info) '

ZSH_THEME_GIT_PROMPT_PREFIX="%{$fg[magenta]%}"
ZSH_THEME_GIT_PROMPT_SUFFIX="%{$reset_color%}"
ZSH_THEME_GIT_PROMPT_DIRTY="%{$fg_bold[red]%} !%{$reset_color%}"
ZSH_THEME_GIT_PROMPT_CLEAN=""
```
