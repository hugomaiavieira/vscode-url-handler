# Visual Studio Code URL Handler on Linux (Ubuntu based)

Enables Visual Studio Code to open URL Scheme vscode://, subl:// and txmt:// like these:

`vscode://open/?url=file:///etc/passwd&line=10&column=2`

## Installation

Download [latest release](https://github.com/hugomaiavieira/vscode-url-handler/archive/master.zip).

Unzip it, then:
``` bash
cd vscode-url-handler-master
bash install
```

## Test it

Open a new tab on your browser and type: vscode://open/?url=file:///etc/hosts

## Thanks

Thierry G. for his [post](http://goo.gl/bO6AZ) and Algorich for the [base sublime project](https://github.com/algorich/sublime-url-handler).
