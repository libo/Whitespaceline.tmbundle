Whitespaceline.tmbundle
=======================

A Textmate 2 bundle that just removes white spaces and adds a newline for you on save.

It simply uses the power of sed and perl incantated from your bash:

```
perl -pe 's/[\t ]+$//g' | sed -a '$a\'
```

## Installation

```bash
mkdir -p ~/Library/Application\ Support/Avian/Bundles/
cd ~/Library/Application\ Support/Avian/Bundles/
git clone git@github.com:libo/Whitespaceline.tmbundle.git
```
