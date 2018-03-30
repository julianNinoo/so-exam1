 

## Primer Examen Parcial 

 Nombre: Julián Niño  
 Código: A00328080  
 Materia: Sistemas Operativos  
 Correo Electronico : julian.nino@correo.icesi.edu.co


 ## Descripción 

En este nuevo repositorio se podrá ver el Primer examen parcial de sistemas operativos , en el cual se instala una imagen del sistema operativo  Debian en Virtual Box tambien la configuracion de mtPutty y de Putty.  

El repositorio antes mencionado se encontrará en este link: https://github.com/julianNinoo/so-exam1.git  

La lista de comandos empleados en este parcial se encontrará en  > comandos-List.txt

 
## Tercer Punto

-Se descargó MD5 del sigiente link http://download.cnet.com/MD5-SHA-Checksum-Utility/3001-2092_4-10911445.html  
-Para obtener el checksum que debemos verificar se ingresa al siguiente link : http://cdimage.debian.org/debian-cd/current/amd64/iso-cd/MD5SUMS ( prueba de esto se4 encuentra en una imagen , abajo ) 
- Se ingresa en el campo  y se hace la respetectiva verificación 

Link de la verificación:  



![](Imagenes/Descarga2.png)  


Verificación:   

![](Imagenes/Descarga1.png)  


## Cuarto Punto 
Se da click en nueva en la Virtual Box, el nombre  se le da como Debian9, el tamaño de memoria no se cambió es decir que esta en 1024 MB, esto creará un disco virtual , se configuran las interfaces de red para la maquina virtual despues de esto se configuró el super usuario ,el idioma y se procede a esperar varias horas para la instalación del sistema operativo.  

En los siguientes comandos se puede ver la información del sistema 


``` 
julian@debian:~/Documentos$ uname
Linux
```
```
julian@debian:~/Documentos$ uname -a
Linux debian 4.9.0-6-amd64 #1 SMP Debian 4.9.82-1+deb9u3 (2018-03-02) x86_64 GNU/Linux
```
```
julian@debian:~/Documentos$ uname -o
GNU/Linux
```
```
julian@debian:~/Documentos$ uname -m
x86_64
```
Imagen de los comandos en esta maquina virtual
![](Imagenes/Descarga3.png) 

 ## Quinto Punto
 
 Se configura la IP de la maquina virtual , la comunicación por medio de SSH, el puerto que usualmente es 22 y el usuario y contraseña para acceder a la maquina virtual 
 
![](Imagenes/Descarga4.png) 

## Sexto Punto

Esta es la evidencia de la instalación de GIT y TIG  
![](Imagenes/Descarga7.png) 


Historial de commits
![](Imagenes/Descarga5.png) 
![](Imagenes/Descarga6.png) 


(apt-get install tig)
![](Imagenes/Descarga8.png) 


## Septimo Punto


## Octavo Punto 

Comparaciones entre CentOS7 y Debian 9 son:

##CentOS7                                           	     ##Debian9
1-La versión más fragil pesa 500MB.                        1-La versión más fragil de Debian9 pesa 300 MB.
2-En el Mercado esta en un 21%.                            2-En el mercado esta en un 32%.
3-La versión del Kernel es de 3.10.                        3-La version del Kernel es 4.9.0.
4-En arquitecturas maneja x86_64.                          4-Aparte de x86 , tambien esta ARM,MIPS.
5-Distribución de GNU/Linux.                               5-Distribución Libre.
6-No tiene un ciclo de vida util.                          6-Ciclo de aproximadamente 10 años.
7-Su fecha de lanzamiento fue en el 2014.                  7-Sé lanzo en el 2017.
8-En el gestor de paquetes se encuentra yum.               8-Aquí está apt-get. 
9-Se utiliza más que todo en servidores.                   9-Puede adaptarse a cualquier necesidad.
10-Es usado en más de 4 millones de sitios web.             10-Es usado menos que CentOS 7 en aproximandamente 3 millones de sitios web.

## Noveno Punto
La URL de mi repositorio es https://github.com/julianNinoo/so-exam1 
