# P02-50
## Ramas en Git
1. He creado un repositorio local donde he añadido un documento de texto y he realizado un commit. Despues, con el comando "git branch carpetaCasa" he creado una nueva rama llamad "carpetaCasa". He realizado un push hacia esta carpeta añadiendo al final del push "carpetaCasa".
2. Mediante el comando "git checkout" he cambiado a la rama master. Ahí he realizado un cambio en el documento de texto, lo he añadido y he hecho un commit y un push en la rama master.
3. He ido a la carpetaInstituto mediante los comandos "cd ..", "cd" y "pwd". En la carpetaInstituto he realizado un pull de la rama master y la rama carpetaCasa con los siguientes comandos: " git pull https://github.com/miguelmartinez22/P02-50 master" y " git pull https://github.com/miguelmartinez22/P02-50 carpetaCasa".
4. He cambiado a la rama master y desde ahí he ejecutado el comando "git merge carpetaCasa -m "Unión master y carpetaCasa"". Así, he unificado ambas ramas.
5. Por último, he accedido al gráfico de github en la pestaña Insights -> Network. Ahí he observado la creación de las distintas ramas con sus commits.
