# Como subir a Github
Estos son los comandos a utilizar.
## Comandos
Iniciar Repositorio
```
git init
```
Si es un proyecto nuevo debemos realizar la conexión con el repositorio de Github
```
git remote add origin https://github.com/milagrossc1/IA

```
Agregando archivos para hacer el comit.
```
//Agrega todos los archivos
git add -A

//Agrega solo el archivo que le indiquemos
git add ejemplo.py

```
Creando el commit
```
git commit -m 'mensaje del commit'

```
Y finalmente subiendo al repositorio de Github
```
git push -u origin master

```
