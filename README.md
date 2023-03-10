# Memoria práctica 1 Git

## Comandos utilizados:

1. winget install git.git
    (Permite instalar GIT en tu ordenador.)

2. git version
    (Permite ver que version de GIT tienes en tu dispositivo.)

3. git config --global user.name "Rodeyro"
    (Permite cambiar el nombre de tu usuario.)

4. git config --global user.email antoniojuradorodeyro@gmail.com
    (Permite cambiar el correo de tu usuario.)

5. git config --list
    (Permite ver información sobre tu usuario.)

6. git init
    (Permite inicar el GIT en tu dispositivo.)

7. git commit -m "Creación do proxecto "
    (Permite guardar lo que hayas hecho hasta el momento.)

8. git branch -M main
    (Permite cambiar el nombre de la rama.)

9. git remote add origin https://github.com/rodeyro/proba-Repos.git
    (Añadir la conesión del git hasta el GITHUB.)

10. git clone https://github.com/rodeyro/proba-Repos.git
    (Hacer una copia de seguridad de tu GIT.)

11. git pull --all
    (Quitar todos los comit que haya habido en el server remoto(GITHUB).)

12. git add .
    (Permite leer los cambios del GIT.)

13. git push -u origin main
    (Manda todo lo hecho hacia el GITHUB.)

14. git log --oneline --graph --decorate --all
    (Permite ver todos los comits realizados y en cual estás.)


## Pasos a seguir: 

1. Instalar git con "winget install git.git"

2. Inicializar repo local con el comado "git init"

3. Crear un nombre de usuario y un correo con "git config --global user.name "Rodeyro"" y "git config --global user.email antoniojuradorodeyro@gmail.com"

4. Después, comprobar con "git config --list" si se ha ejecutado el anterior paso correctamente

5. Proseguimos con el comando "git remote add origin https://github.com/rodeyro/proba-Repos.git" que nos permite crear un enlace entre nuestros trabajos hasta el repos para poder proseguir.

6. Finalmente para guardar cualquier cosa que realicas, tendrías que hacer estos 3 comandos: "git add ." para leer los cambios del GIT, "git commit -m "Creación do proxecto "" ( Si quieres ver que comits tienes hasta ese momento, "git log --oneline --graph --decorate --all" ) para guardar todo lo que hiciste hasta el momento y "git push -u origin main" para mandarlo todo a tu main.


## Nuevos comandos: 

1. git status
    (Permite ver el estado de tu trabajo actual)
    
2. git add "texto"
    (Hace lo mismo que "git add ." aunque ahora podrás selecionar lo que quieres guardar o no)
    
3. git diff "..." , "..."
    ( Permite establecer las diferencias en los orígenes de datos de Git)
    
4. git show
    (Permite mostrar los datos actuales de tu trabajo coo por ejemplo tu commit actual)
    
5. git commit --around -m "texto"
    (Modifica el último commit añadido)

6. git reset --hard 8c808
    (Permite volver al commit seleccionado)

7. git remote remove origin
    (Permite remover el primer commit)
    
8. git log
    (permite ver el historico dos commits)
    
9. git annotate "..."
    (permite ver todos los cambios y quienes los hayan realizado en un archivo)
    
10. git checkout -- indice.txt
    (permite desacer los cambios de un archivo)
    
11. git reset indice.txt
    (permirte resetear un fichero)
    
12. git clean -f
    (borrar fichero que hayamos agragado en el último commit)
    
13. git reset --hard HEAD~1    
    (permite volver a donde estaba, pero descartará sus cambios locales, que no desea)

14. git reset --soft HEAD~1
    (elimine la última confirmación de la rama actual, pero los cambios en el archivo permanecerán en su árbol de trabajo)
    
15. git branch bibliografia
    (Permite crear una rama)
    
16. git branch -av
    (mostrar las ramas del repositorio.)
    
17. git checkout bibliografia
    (Permite cambiar de rama a la deseada)
    
18. cat > bibliografia.txt
    (Permite craear un fichero con el nombre a tu gusto)
    
19. git merge bibliografia
    (Mostrar la historia del repositorio incluyendo todas las ramas.)
    
20. git branch -d bibliografia
    (Eliminar una rama)

21. git merge bibliografia
    (Fusionar varias ramas en una)
    
22. git nano bibliografia
    (esolver conflictos dejando el fichero con algunas preferencias)    
