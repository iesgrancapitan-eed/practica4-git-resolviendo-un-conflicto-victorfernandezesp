Asegúrate de que tienes configurado el editor Visual Studio Code como tu editor de Git. (git config --global core.editor "code --wait")
![alt](1.jpg)
Crea un repositorio local y avanza en la rama "master" añadiendo un fichero "index.html" con la estructura básica html. El body estará vacío
![alt](2.jpg)
Crea y salta a "rama-1". Avanza en un commit con tu nombre de pila en un párrafo dentro del body
![alt](3.jpg)
Vuelve a la rama master
![alt](4.jpg)

Crea y salta a "rama-2". Avanza en un commit con tu apellido en un párrafo dentro del body
![alt](5.jpg)

Muestra el estado del repositorio de forma gráfica y resumida


Haz un merge a rama-1. Intentas fusionar ambas ramas. Aparecerá un conflicto porque ambos commits trabajan en la misma porción <body></body> de un mismo archivo index.
![alt](6a.jpg)
![alt](6b.jpg)
html. Git no será capaz de fusionarlas directamente. 

El editor VS Code reconoce los conflictos de fusión. Las diferencias se resaltan y hay acciones en línea para aceptar los cambios. Deja un único párrafo con tu nombre 
de pila y apellido.

Una vez que se resuelto el conflicto confirma el archivo en conflicto para que pueda realizar esos cambios
![alt](7.jpg)
Muestra de nuevo el estado del repositorio de forma gráfica y resumida
![alt](8.jpg)
Vuelve a la rama master y realiza otro merge. Es una fusión fast-forward. Los dos commits a fusionar tienen relación de ancestro. Entonces el merge no produce un commit 
nuevo, sencillamente avanza la rama, "avance rápido"
![alt](9.jpg)
Visualiza las ramas que han sido fusionadas con la rama master
![alt](10.jpg)
Elimina las ramas correctamente fusionadas (sin asterisco) para quedarte SOLO con la rama master. 
![alt](11.jpg)
Realiza una copia a este repositorio remoto

Recuerda añadir estas instrucciones con los pantallazos en el fichero README.md

En GitHub entra en Insights/network y visualiza el gráfico del repositorio con los merge y cinco commits  