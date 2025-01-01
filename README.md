# Dotfiles

## Clonar

Clonar en ~/.dotfiles
```git
git@github.com:guidogimeno/.dotfiles.git
```

## Instalar GNU Stow
```bash
sudo apt install stow
```

## Crear los symlinks

### Crear los archivos dentro de la carpeta .dotfiles

```bash
mkdir -p ~/.dotfiles/ejemplo/.carpeta1/carpeta2/archivo
```

Esta va a ser la ruta: 
**~/.carpeta1/carpeta2/archivo**

### Crear los symlinks
```bash
cd ~/.dotfiles

stow ejemplo
```
