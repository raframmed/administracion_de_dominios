# Administración de dominios
## A)	Se han implementado dominios.
Un Dominio es una colección de objetos dentro del directorio que forman un subconjunto administrativo. 
Pueden existir diferentes dominios dentro de un bosque, cada uno de ellos con su propia colección de objetos y 
unidades organizativas.

Para poner nombre a los dominios se utiliza el protocolo DNS. Más adelante configuraremos servidores DNS para poder usar 
el Active Directory.

### Asignación de dirección IP, máscara de red y servidor DNS al servidor
Antes de crear un domino deberemos asignar una dirección IP al adaptador de red junt con su máscara de red y también 
un servidor DNS para que el servidor pueda tener acceso a internet. Para ello haremos uso del *sconfig.md*. Al ejecutarlo
nos encontraremos lo siguiente:

![alt text](https://github.com/raframmed/administracion_de_dominios/blob/master/assets/images/sconfig_cmd.png "sconfig.cmd")

Como podemos observar en mi caso ya tengo configurada una dirección IP con su máscara y un servidor DNS. Para ello deberemos 
seleccionar la opción 8 del menú que se nos muestra, la cual nos llevará al siguiente submenú:

![alt text](https://github.com/raframmed/administracion_de_dominios/blob/master/assets/images/adaptador_sconfig.png "adaptador_sconfig.cmd")



