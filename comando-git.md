# Comando de gif

//////////////////////////////////////////////////////////////////////////////////////////////////////

## git config --global init.defaultBranch main
```

Cambia la rama principal de git, de la MASTER a la MAIN

```

## git checkout -- .
```
Regresa al ultimo commit recuperando los archivos borrados

```

## git add (carpeta)/*.(extencion) 

```
agregar las extensiones de toda la carpeta 

git add css/

agregar todo lo que hay en las carpetas

```


##  crear archivo .gitkeep

```
esto sirve para carpetas vacias que git no reconoce y al agregar este archivo de git le estamos diciendo a git que la detecte

```


## Crear alias para los comandos 


```
git config --global alias.nombreDelAlias (comando a ejecutar)

```



## creando alias para ver los log de manera mas eficiente

```

git config --global alias.lg "log --graph --abbrev-commit --decorate --format=format:'%C(bold blue)%h%C(reset) - %C(bold green)(%ar)%C(reset) %C(white)%s%C(reset) %C(dim white)- %an%C(reset)%C(bold yellow)%d%C(reset)' --all"

```


## git diff 

``` 
nos muestra los que estamos cambiando ...


```


## git commit --amend -m 'ACTUALIZAR commit'

```
permite editar el mensaje del commit por si lo escribimos mal

```


## git reset --soft HEAD^

```
 REGRESA AL COMMIT ANTERIOR ^1,2,3

```







