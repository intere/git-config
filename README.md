# Git Config
This repo contains some (from my experience) helpful git configuration.  The files:

* ``.git-completion.bash`` - Auto completion support for git with bash (if you use zsh, it's a plugin)
* ``.gitconfig`` - Some helpful configuration (colors, etc) and aliases for git (e.g. git lga)
* ``git-completion.bash`` - symlink to the "dot" version of this file (you might not be able to see the dot version in your file browser)
* ``gitconfig`` - symlink to the "dot" version of this file (you might not be able to see the dot version in your file browser)

## Usage
1. Clone this Repo
2. ```cp .gitconfig ~/```  # Copy the file over to your home directory
3. edit ``~/.gitconfig`` (the last 2 lines are your name and email address)

```
[user]
  name = YourName Here
  email = username@domain.com
```

## Bash
Copy the git completion bash script to your home directory
```bash
cp .git-completion.bash ~/
```

Add the following to your ``.bashrc`` file:
```bash
source ~/.git-completion.bash
```

## Zsh
Ensure you have git in your plugins configuration in your ``.zshrc`` file:
```zsh
plugins=(git gitfast npm node bower gem mvn osx sublime brew vagrant)
```
