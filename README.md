:feelsgood: **mdlive** - Live preview your md file in browser

# Table of Contents
* [Installation](#installation)
* [Usage](#usage)
* [References](#references)

# Installation

1. Install dependencies

**`entr`**
```sh
hg clone https://bitbucket.org/eradman/entr
cd entr
./configure
make test
sudo make install
```

**`pandoc`**
```sh
sudo pacman -S pandoc
```

**`http-server`**
```sh
npm install --global http-server
```
---

2. Clone this repo
```sh
(https)
git clone https://github.com/henriqcs/mdlive.git

(ssh)
git clone git@github.com:henriqcs/mdlive.git
```
---

3. Run configure script and reload `.bashrc`
```sh
cd mdlive
./configure
source ~/.bashrc
```

# Usage
`mdlive <MDFILE>` Starts live preview of md file.

`mdclean [<MDFILE>]` Stops live preview and clean the environment.

`mdconv <MDFILE>` Converts md file to html.

# References
- [GitHub Markdown](https://guides.github.com/features/mastering-markdown/#GitHub-flavored-markdown)
