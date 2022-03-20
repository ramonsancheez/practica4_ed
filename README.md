# practica4_ed

Para la realización de esta práctica, el primer paso que necesitamos llevar a cabo, es la clonación del proyecto a nuestro local:
<img width="600" alt="image" src="https://user-images.githubusercontent.com/91556453/159168300-f420e27a-e386-4311-a2b0-bfa4c5fbc8ef.png">

De este modo, obtendremos el proyecto en nuestro ordenador:
<img width="600" alt="image" src="https://user-images.githubusercontent.com/91556453/159168425-a6d64ce3-39a1-49c5-8ef3-712dd4f76bde.png">

Una vez clonado el repositorio, será necesario que vayamos a las tags del repositorio para coger la versión que queramos, en nuestro caso, la v.1.1.0:

<img width="600" alt="image" src="https://user-images.githubusercontent.com/91556453/159168682-d622bf09-d7e8-4d89-b37f-e2cedd90d793.png">

Obtenemos el número seleccionado, y mediante el siguiente comando nos movemos entre los commits y las ramas para volver a la versión v1.0.0:
```
git checkout 8562b03
```

Cuando ya tenemos la versión deseada, es necesario eliminar la carpeta .git, así que la eliminamos, y mediante los siguientes comandos, inicializamos otra vez el repositorio:
```
git init
git remote add origin https://github.com/ramonsancheez/practica4_ed.git
```

eso es lo que tienes que hacer tu, clonas el repo, refactorizas dos cosas en develop (haces un refac y haces add y commit, y creas una tag nueva (sería la v1.3.0), despues, vuelves a hacer otro refact,add, commit y tag (v1.4.0), y en master los mergeas
git add
git commit
git tag v1.X.0
git push -u origin rama_principal
git push --tags 

escribe en el readme las dos refacts que haces, y mira de poner comentarios javaDoc
