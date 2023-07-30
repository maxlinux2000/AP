# AP
**Tengo la corazonada que dentro de poco internet será un recuerdo.**  
Ya se que hay motivos muy poderosos para que esto no vaya a ocurrir nunca, pero tampoco es imposible.  
Hay muchas posibilidad sea económicas, políticas o de guerra para que algo tan maravilloso y precioso como es internet, sea destruido por lo menos en las partes más importantes.  
No estoy considerando de propósito un desastre natural como una tormenta solar mucho más fuerte del Evento Carrintong como fue el Evento Carlo Magno (X20 evento Carrintong).  
E contra de esto no tenemos defensa eficaz, y es tan improbable que no puedo tenerlo en cuenta.  
O sea que considero mucho más peligroso el ser humano que la naturaleza. No es la primera vez que el ser humano deja caer en el olvido estructuras tan importantes como fueron los acueductos y red de carreteras o ferrovial en tiempos recientes.  
  
Así que la idea es de poner a salvo de forma lo más distribuida posible todo el material valioso que se encuentra en internet.  
Para material valioso personalmente yo excluyo cualquier película, series, novelas, ensayos literario en los últimos 100 años. En mi opinión hay como mucho unas 10-15 películas que merecen ser puesta a salvo, el resto para mi puede caer en el olvido de la historia.  
Non obstante dejo completa libertad de lo que cada uno considera importante y digno de ser puesto a salvo.  
Voy a poner a disposición una lista de enlaces de canales y sitios web con material que to considero importante, luego cada uno haga lo que considera oportuno.  
  
**¿Porqué en español en lugar que el inglés?**  
Esta es otra corazonada. Me parece que el inglés va a terminar como el latín, y por lo tanto me centro en lo que yo considero oportuno… y considerar que este no es mi idioma madre ni lo hablo ni lo escribo particularmente bien.  
Pero considero que el español va a ser el idioma más importante dentro de poco tiempo, mientra que el inglés va a perder su papel de lengua internacional.  
Repito... Es una corazonada, no tengo explicaciones plausibles para ofrecer.  
Así que si alguien quiere traducir al inglés, u otro idioma, este trabajo, es libre de hacerlo.  
  
**¿Porqué Bash en lugar de C++ o python o javascript o…. ?**  
Por simplicidad. 
Considera esto:  
En un futuro habrá algún desarrollador novato que tendrá una copia de AP en su equipo obsoleto, no tendrá internet para hacer búsquedas en stakoverflow ni tendrá acceso a todas las librerías de pro ejemplo C# o python (pip install ... no funciona sin internet a menos que no tengas un mirror local)  
Así que me he basado en el mismo sistema operativo Gnu/Linux. Como hace para hacer funcionar lo básico? Script de shell, y la shell que hay por defecto, es Bash.  
Por esto he pensado que programar en Bash es lo ideal. Viene por defecto, tiene todo lo necesario en el sistema mismo, es relativamente fácil de usar y la eficiencia o la velocidad no es fundamental en nuestro caso. Para un escenario así lo importante es que funcione y sea fácil de modificar si hace falta, aunque sea 10 veces mas lento.  
Si tienes que salir en un monte sin carretera con un coche, es mejor usar un todoterreno que un ferrari o un porche.  
  
**¿Porqué HTML?**  
Hay motivos:  
1) En bash es muy fácil generar páginas web estáticas  
2) servir una pagina html es mucho más liviano que una dinámicas para un servidor  
3) no necesitamos de ninguna interacción a parte poder leer paginas o ver videos  
Une todo esto al hecho que es muy probable que no tengamos servidores ultra potentes, si no viejos ordenadores de bajo consumo.

**¿Porqué Ubuntu 22,04 LTS?**  
Porqué funciona. Pero no lo tomes a mal. E usuario de destino es una persona que no sabe casi nada de informática, y para el es un problema insormontable que no funcione por ejemplo la tarjeta audio porqué le falta por ejemplo el firmware no libre.  
Estoy de acuerdo que se tendría que usar siempre software libre, pero esto se puede hacer en buenos tiempos cuando puedes ir a supermercado o en ebay y elegir un ordenador que contenga solo hardware suportado por el software libre.  
Pero este proyecto es para tiempos bastante oscuros donde hay muchos problemas e encontrar piezas, informaciones, y hasta comida.  
Así que lo más sensato es usar sistemas que puedan funcionar por todas partes sin tener acceso a internet.  
En el momento en que escribo todavía no tenemos un sistema de instalación totalmente offline, pero estamos en ello y espero tenerlo pronto.  
  
**¿Debian 11?**  
Pero no todo es Ubuntu, tenemos también a Debian 11 que estamos usando en AP Extra 1 junto con Yunohost.  
Claramente he tenido que instalar todos los firmware non-free disponibles. Esto ha sido necesario para asegurarme que AP-Extra 1 funcione con cualquier hardware no demasiado reciente.  
El día que Yunohost pase a Debian12, haremos una actualización.

