Se añadieron todos los archivos necesarios para el proyecto Clinica Veterinaria
Anexo estructura en el terminal
PS C:\Users\LUIS SALINAS\Desktop\Curso de pagina web\Projectos nuevos 31052024\Proy01-Clinica_Veterinaria> git config --global user.name "lmsu"
PS C:\Users\LUIS SALINAS\Desktop\Curso de pagina web\Projectos nuevos 31052024\Proy01-Clinica_Veterinaria> git config --global user.email "lsalinasuban@hotmail.com"
PS C:\Users\LUIS SALINAS\Desktop\Curso de pagina web\Projectos nuevos 31052024\Proy01-Clinica_Veterinaria> git config --global push.defaul "maching"
PS C:\Users\LUIS SALINAS\Desktop\Curso de pagina web\Projectos nuevos 31052024\Proy01-Clinica_Veterinaria> git init
Reinitialized existing Git repository in C:/Users/LUIS SALINAS/Desktop/Curso de pagina web/Projectos nuevos 31052024/Proy01-Clinica_Veterinaria/.git/
PS C:\Users\LUIS SALINAS\Desktop\Curso de pagina web\Projectos nuevos 31052024\Proy01-Clinica_Veterinaria> git add index.html
PS C:\Users\LUIS SALINAS\Desktop\Curso de pagina web\Projectos nuevos 31052024\Proy01-Clinica_Veterinaria> git commit -m "Commit inicial anexar archivo index.html"
[master (root-commit) 695540e] Commit inicial anexar archivo index.html
 1 file changed, 463 insertions(+)
 create mode 100644 index.html
PS C:\Users\LUIS SALINAS\Desktop\Curso de pagina web\Projectos nuevos 31052024\Proy01-Clinica_Veterinaria> git log
commit 695540e55f8e3dc4d2cbb518e5209da108c1b7d0 (HEAD -> master)
Author: lmsu <lsalinasuban@hotmail.com>
Date:   Tue Nov 5 11:13:46 2024 +0100

    Commit inicial anexar archivo index.html
PS C:\Users\LUIS SALINAS\Desktop\Curso de pagina web\Projectos nuevos 31052024\Proy01-Clinica_Veterinaria> git remote add origin https://github.com/lmsu/proy01-clinica-veterinaria.git
PS C:\Users\LUIS SALINAS\Desktop\Curso de pagina web\Projectos nuevos 31052024\Proy01-Clinica_Veterinaria> git add css
PS C:\Users\LUIS SALINAS\Desktop\Curso de pagina web\Projectos nuevos 31052024\Proy01-Clinica_Veterinaria> git add img
PS C:\Users\LUIS SALINAS\Desktop\Curso de pagina web\Projectos nuevos 31052024\Proy01-Clinica_Veterinaria> git log
commit 695540e55f8e3dc4d2cbb518e5209da108c1b7d0 (HEAD -> master)
Author: lmsu <lsalinasuban@hotmail.com>
Date:   Tue Nov 5 11:13:46 2024 +0100

    Commit inicial anexar archivo index.html
PS C:\Users\LUIS SALINAS\Desktop\Curso de pagina web\Projectos nuevos 31052024\Proy01-Clinica_Veterinaria> git commit -m "agregar carpeta css y carpeta img"
[master 34c48af] agregar carpeta css y carpeta img
 14 files changed, 489 insertions(+)
 create mode 100644 css/style.css
 create mode 100644 img/comida20.png
 create mode 100644 img/comida21.png
 create mode 100644 img/comida22.png
 create mode 100644 img/comida23.png
 create mode 100644 img/comida30.png
 create mode 100644 img/comida31.png
 create mode 100644 img/comida32.png
 create mode 100644 img/comida33.png
 create mode 100644 img/facebook.png
 create mode 100644 img/img1.jpeg
 create mode 100644 img/instagram.png
 create mode 100644 img/logo.png
 create mode 100644 img/twitter.png
PS C:\Users\LUIS SALINAS\Desktop\Curso de pagina web\Projectos nuevos 31052024\Proy01-Clinica_Veterinaria> ls


    Directorio: C:\Users\LUIS SALINAS\Desktop\Curso de pagina web\Projectos nuevos 31052024\Proy01-Clinica_Veterinaria


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----        12/06/2024     10:13                .vscode
d-----        02/06/2024     13:27                css
d-----        02/06/2024     13:27                img
d-----        04/11/2024     13:38                Proyecto-veterinario
-a----        05/06/2024     14:25           1113 app.js
-a----        05/06/2024     14:32           1416 app1.js
-a----        12/06/2024     10:06           2575 copia.txt
-a----        03/06/2024      9:56            726 Ej01.js
-a----        03/06/2024     10:42           1124 Ej02.js
-a----        03/06/2024     11:33           1130 Ej02a.js
-a----        03/06/2024      9:43           1512 Ejemprof.js
-a----        03/06/2024     11:34           2288 Ejercicio3.js
-a----        03/06/2024     11:45          25689 index.html
-a----        15/04/2024     12:29           4817 index23.html
-a----        05/06/2024     14:34           1137 index24.html
-a----        12/06/2024     10:19            498 indexppal.html
-a----        04/06/2024     11:53           1657 lsalinas.html
-a----        03/06/2024     11:11            128 otro.css
-a----        03/06/2024     11:35           1007 otro.html
-a----        02/06/2024     14:59           1772 usuario.txt

PS C:\Users\LUIS SALINAS\Desktop\Curso de pagina web\Projectos nuevos 31052024\Proy01-Clinica_Veterinaria> git branch -M main
PS C:\Users\LUIS SALINAS\Desktop\Curso de pagina web\Projectos nuevos 31052024\Proy01-Clinica_Veterinaria> git push -u origin main
Enumerating objects: 21, done.
Counting objects: 100% (21/21), done.
Delta compression using up to 12 threads
Compressing objects: 100% (19/19), done.
Writing objects: 100% (21/21), 2.62 MiB | 1.86 MiB/s, done.
Total 21 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/lmsu/proy01-clinica-veterinaria.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.
