##MPLABX IDE

En esta guía mostraremos como programar un micro controlador con la IDE MPLABX, 
utilizando como ejemplo un programa con el cual controlaremos 2 LED con un botón.
Lo primero que debemos hacer es crear nuestro proyecto, 
para eso iremos a la pestaña “New Project” y seguiremos los pasos a continuación .
 
 
- ![uno](https://i.ibb.co/b5p21nx/uno.png).
- ![dos](https://i.ibb.co/z5Mr2XL/dos.png).
- ![tres](https://i.ibb.co/m57BxwF/tres.png).

Aquí seleccionaremos el chip que queremos utilizar, 
elegimos el **PIC18F47K40** ya que podremos simularlo en Proteus.

- ![cuatro](https://i.ibb.co/k2fTJfn/cuatro.png).
- ![cinco](https://i.ibb.co/xX50HtV/cinco.png).
- ![seis](https://i.ibb.co/kHyqbcz/seis.png).
 
En este ultimo paso deberemos nombrar a nuestro proyecto, 
nosotros utilizaremos el nombre *“ejemplo”*.
Una vez creado nuestro proyecto debemos crear un archivo *“main.c”* para eso seguiremos los siguientes pasos.

- ![siete](https://i.ibb.co/NYvfLQ8/siete.png).
 
Seleccionamos *“Source Files”*, luego *“New”* y por ultimo *“main.c”*.
Una vez creado el main.c podremos comenzar a programar en el, para esta guía utilizaremos un código ya hecho. Primero debemos configurar los pines I/O.

- ![ocho](https://i.ibb.co/7bJvgzv/ocho.png).

Luego debemos tomar el valor de nuestro pin de entrada (en nuestro caso A1) y luego configurar los pines de salida (B1 y B2).
 

En este caso cuando, presionemos el botón, el LED *B1* encendera y el *LED B2* se pagara, cuando soltemos estos cambiaran.
Luego de programar nuestro código debemos compilarlo y enviarlo al micro, para esto utilizaremos la herramienta *“Clean and Build Main Project”*.
 
- ![nueve](https://i.ibb.co/RTzYkgj/nueve.png).

Esta herramienta buscara errores en el código y en caso de no haber ninguno compilara el programa. 
Una vez compilado debemos enviarlo al micro, 
para eso buscaremos en la carpeta del proyecto el archivo “.HEX”.
 
- ![diez](https://i.ibb.co/zm2197S/diez.png).

Una vez encontremos el archivo simplemente debemos copiarlo y pegarlo al micro, el cual conectaremos mediante un cable USB al equi.

###espero que les haya servido esta informacion, buena suerte
