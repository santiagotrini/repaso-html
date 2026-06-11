# Esto es un repaso de HTML + CSS + Git

Es para la prueba de mañana, estudien!

```console
$ mkdir repaso-html
$ cd repaso-html
$ git init &> /dev/null
$ git remote add origin https://github.com/santiagotrini/repaso-html
$ git config user.name "Santiago Trini"
$ git config user.email "santiagotrini@gmail.com"
$ touch README.md styles.css index.html
```

Primeros commits

```console
$ git add README.md
$ git commit
$ git add .
$ git commit -m "lo que quieras"
```

Subimos al remoto

```console
$ git push -u origin master
```

Después seteamos GH Pages.
