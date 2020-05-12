# Gedit

Es un editor de texto el cual ya puedes colorear el código de Latino, sigue las instucciones

```
cd ~
git clone  https://github.com/lenguaje-latino/Latino-Gedit-Plugin.git 
cd Latino-Gedit-Plugin
chmod +x install.sh
sudo ./install.sh
```

> Después debes escojer el modo de coloración "Latino" en las opciones

## Explicación

En si lo que hacemos es copiar el fichero **latino.lang** en la carpeta

## /usr/share/gtksourceview-%/language-specs

o bien en la carpeta personal

## ~/.local/share/gtksourceview-%/language-specs

Esto hara que Gedit reconosca "Latino" y va a colorear el código

Nota: El simbolo por siento debe ser sustituido por la version de gtk con que se cuenta.

