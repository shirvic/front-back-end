* Para poder ver la version de git ejecutamos en 
nuestra terminal:
```

git --version

git -v

```
* Para configurar el correo y nombre (sólo la primera vez en mi máquina)

```
git config --global user.email "micorreo@gmail.com"

git config --global user.name "Mi nombre"

```
* Para ver la configuración de git

```
git config --list

```
* Para inicializar nuestro repositorio en git:

```
git init

```
* Para ver el estado de nuestro cambios:

```
git status

```
* Para preparar nuestros archivos para la zona de stage (prepararlos para commit)

```
git add .

git add nombreDelArchivo.extensión

```

* Crear el registro de los cambios realizados:

```
git commit -m "comentario corto y conciso"

```
* Para ver una linea de tiempo de los commits que hemos realizado:

```
git log

```
* Para poder ver el detalle de un commit específico 
usamos:

```
git show id-de-commit
```