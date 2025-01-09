## **Git**
### _Crear repositorios git y subirlos a github_

---

> [Abrir GitHub](hhttps://github.com/) y crear un repositorio en la nube llamado p.e. GitLab. 
>
>(Utilizaremos esta mickey-herramienta más tarde)

>Para crear nuestro repositorio local:
> 1. Creamos una carpeta contenedor para nuestro repositorio en local y le añadimos un archivo p.e. "readme.md".
> 2. Nos situamos desde cmd en la ubicaión de la carpeta o la abrimos en vsc y ejecutamos git init.
> 3.  Ejecutamos git add .  para añadir todos los archivos, en este caso solo readme.md, y poder commitearlos
> 4. Ejecutamos git commit -m "descripcion variable" para commitear lo que hemos añadido anteriormente y asignarle una descripcion
> 5. Si editamos nuestro archivo lo volvemos a commitear asignándole una nueva descripción.

Ya tenemos nuestro repositorio actualizado.

> Para subir nuestro repositorio local a la nube:
> 1. Copiaremos la URL de nuestro repositorio en github.
> 2. Ejecutamos git remote add origin "nuestra URL"
> 3. Ejecutamos git push -u origin master 

Listo, ya tenemos nuestro repo en la nube

>Para crear una nueva rama: 
> 1. Checkeamos las ramas que tenemos actualmente ejecutando git branch, en este caso únicamente tenemos master, nuestra rama principal.
> 2. Creamos una rama nueva ejecutando git switch -c "development"
> 3. Hacemos un commit a esta nueva rama y pusheamos a nuestro repo en la nube para comprobar que marcha bien 


Algunas imágenes del proceso: 

![placeholder](/img/img-1.jpg)
![placeholder](/img/img-2.jpg)
![placeholder](/img/img-3.jpg)
![placeholder](/img/img-4.jpg)
![placeholder](/img/img-5.jpg)


Gracias :)
