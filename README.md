Source Code Pro Font
====================

## Objective
```
Installer une police de caracteres pour le code.
```

## How to install
### Download Font archive
With **shyganer** in **/tmp/**

wget https://github.com/adobe-fonts/source-code-pro/archive/2.030R-ro/1.050R-it.tar.gz

### Extract archive file
With **shyganer** in **/tmp/**

gunzip -c adobe-source-code-pro-fonts.tar.gz | tar -xf -

### Install fonts for current user
With **shyganer** in **/tmp/**

```
mkdir -p $HOME/.fonts

cp adobe-source-code-pro-fonts/*.[oft|ttf] $HOME/.fonts
```
### Add to lxapparance
With **shyganer** in **/tmp/**

lxapparance > fonts > Source Code Pro

### Add to termite
With **shyganer** in **/tmp/**

sed -i s/font = envypn 9/Source Code Pro 11/g .config/termite/config

### Add to urxvt
With **shyganer** in **/tmp/**

```
sed -i s/URxvt*font: /URxvt*font:xft:Source Code Pro Regular:size=10/g $HOME/.Xresources
```

## How to use
```
```

## Useful commands
```
```

## Errors
```
```

## Bugs
```
```

## Tips
```
1Il|iO0oB8
```

## Todo
* Linker correctement la police de caracteres pour urxvt

## References
1. https://github.com/adobe-fonts/source-code-pro
2. https://github.com/adobe-fonts/source-code-pro/releases/tag/2.030R-ro/1.050R-it.
3. http://chriskempson.github.io/base16/
4. https://terminal.sexy
