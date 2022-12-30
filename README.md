# Retraducción al Español - Digimon World (PSX)
Parche realizado por Dark_Kudoh, Loud Kuyuki y uzuhenry.

Este es un parche que traduce el juego Digimon World al Español desde el japonés. La versión que nos llegó a Europa vino con una traducción terriblemente incomprensible, un montonazo de bugs y errores que afectaban al gameplay, y la imposibilidad directa de pasarse el juego en nuestro idioma.

Este parche aspira a no sólo corregir eso, sino a proporcionar una experiencia rica y lo más óptima posible. Hemos traducido el juego entero desde el japonés, todo el texto del juego está traducido, desde menús a gráficos. Esto acompañado a usar de base la versión japonesa no sólo nos libra de infinidad de bugs, sino que el gameplay es completamente diferente y mucho más dinámico en los combates. 

Pero no nos quedamos ahí. Hemos solucionado también muchos bugs que tenía el juego, hemos añadido unas cuantas mejoras de jugabilidad, y alguna que otra sorpresa ;) . ¡Esperamos que lo disfrutéis mucho!

Algunos bugs que solucionamos son:
  + La música ya no se reinicia a cada cambio de mapa.
  + Tanemon ya no tiene un bloqueo evolutivo al tener ataque como stat principal.
  + Solucionados varios triggers de conversaciones que no se daban.
  + Gekomon por fin se une realmente a la ciudad.
  + Bug de sonido en los créditos solucionado.
  + Y montones de bugs del script y otro pequeños errores.

Este parche no habría sido posible sin la ENORME ayuda proporcionada por:
  - Romsstar
  - SydMontague
  
También queremos agradecer por su inestimable ayuda a:
  - CUE
  - IlDucci
  - Hormox
  - Mheerkino
  - Leviatarius
  
  El randomizer se hizo basándose en el randomizer de la versión americana: https://github.com/SydMontague/digimon_world_randomizer
  
# Intrucciones de uso
+ 1 Seleccionar la imagen original japonesa ( .iso , si es .bin, cambia el nombre al archivo por .iso ).
+ 2 Seleccionar la ubicación y nombre del archivo parcheado que se generará.
+ 3 Seleccionar las opciones de randomización deseadas.
+ 4 Hacer click en el botón "PARCHEAR".

![Intrucciones de parcheo](https://user-images.githubusercontent.com/1196587/208897500-e25dac5b-5117-4175-9086-fb8bd2fa089c.png)

Puede ser necesario instalar .NET
https://dotnet.microsoft.com/es-es/download/dotnet/thank-you/runtime-desktop-6.0.12-windows-x64-installer?cid=getdotnetcore

# Descargar

Puedes consultar el changelog aquí: https://github.com/uzuhenry/DW-ESP-retranslation/blob/main/Changelog.md

  + **[V1.1] 30/12/2022** - https://drive.google.com/file/d/1IumwkOTIXQgYiDToaNhL43pEwoq2L_s0/view?usp=sharing
  
  + [V.100] 22/12/2022 - https://drive.google.com/file/d/1LuY4Ri7UcpILw0W6nLdzCahOr4tDlBJm/view?usp=sharing


# Emuladores compatibles
+ Versión 1.1
  La versión 1.1 soluciona el problema con el check anti piratería, lo que hace que sea compatible con muchos más emuladores y sistemas. Iremos actualizando la lista conforme la comunidad nos comunique compatiblidades.
  
  - DuckStation (Recomendado)
  
+ Emuladores de PC
  - ePSXe + Bios HLE (Recomendado) [Recordad, la velocidad de CPU está a 0x por defecto, ponedla a 1x]
  - no$psx
  - Psxfin (ligeros errores de sonido)
  - XEBRA
  
+ Emuladores móviles
  - EmuPSX XL (Recomendado)
  - XEBRA
  
+ Emuladores con compatibilidad reducida
  - Retroarch con PCSX ReArmed (Problemas de sonido)

Las recomendaciones se basan única y exclusivamente en el rendimiento del juego parcheado en los mismos.

# Problemas conocidos
A continuación enumeramos algunos problemas gráficos leves que no hemos podido solucionar.

+ Bug del banco
 
  Al abrir el menú del banco, las dos listas no se muestran correctamente. Este fallo es únicamente visual.
  
  Esto se puede solventar simplemente bajando hacia abajo y volviendo a subir en la lista para que los objetos se muestren correctamente.
  Así mismo, los objetos que se muestran entre el banco y el inventario se alternan al mover objetos de uno al otro.
  
  ![Bug del banco](https://user-images.githubusercontent.com/1196587/208896323-9c3b0a4f-d6e9-4e71-bd1c-df53c3405818.gif)
  
+ Bug al vender cartas
 
  Al intentar vender cartas, las cifras de unidades y precio se descolocan. Este fallo es únicamente visual.
  
  El precio es el mismo, es un bug leve que no hemos podido solucionar.
  
  ![Bug vender cartas](https://user-images.githubusercontent.com/1196587/208896452-8f8a32f4-4755-4a78-9173-626e65a71f77.gif)
  
+ Bug al ser herido

  Al resultar herido, el mensaje dice "xmon dio está herido". Este fallo es debido a la construcción de los mensajes en japonés. Es un bug sólo visual.
  
  ![Bug herido](https://user-images.githubusercontent.com/1196587/209391426-0a5b00eb-99aa-47a7-af32-25d477b5a4f1.png)

