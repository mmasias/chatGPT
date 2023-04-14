# ChatGPT

> ***Actualización*** La transcripción completa de la charla que se tuvo con ChatGPT durante la sesión [está aquí](sesionChatGPT.md).

## ¿Por qué?

|||
|-|-|
Orígenes (1940-1950)| Alan Turing propone la [prueba de Turing](https://es.wikipedia.org/wiki/Prueba_de_Turing) (1950) como un criterio para la inteligencia artificial / Desarrollo de máquinas y dispositivos electrónicos tempranos, como la máquina de Turing y la computadora ENIAC.
Inicio de la IA como campo académico (1956)| [Conferencia de Dartmouth](https://es.wikipedia.org/wiki/Conferencia_de_Dartmouth), donde se acuña el término "inteligencia artificial" / Participación de figuras clave como Marvin Minsky, John McCarthy, Allen Newell y Herbert Simon.
Enfoque en el simbolismo y la resolución de problemas (1950-1960)| Programas tempranos de IA, como los avances de [Arthur Samuel](https://es.wikipedia.org/wiki/Arthur_L._Samuel) relativos al ajedrez y el programa [General Problem Solver](https://es.wikipedia.org/wiki/General_Problem_Solver) (GPS) de Newell y Simon / Representación del conocimiento y manipulación de símbolos
IA basada en conocimientos (1970-1980)|Sistemas expertos, como MYCIN y DENDRAL, que utilizan bases de conocimientos y reglas de inferencia / Desarrollo de lenguajes de programación de IA, como LISP y Prolog
Aprendizaje automático y redes neuronales (1980-1990)|Algoritmos de aprendizaje supervisado, como el perceptrón multicapa y las máquinas de vectores de soporte / Retropropagación, un algoritmo eficiente para entrenar redes neuronales
Agentes inteligentes y enfoques híbridos (1990-2000)|Combinación de técnicas de IA simbólica y conexionista / Desarrollo de agentes inteligentes y sistemas multiagente / IBM Deep Blue derrota al campeón mundial de ajedrez Garry Kasparov (1997).
Aprendizaje profundo y big data (2010-presente)|Avances en el aprendizaje profundo, con redes neuronales convolucionales (CNN) y recurrentes (RNN) / Aplicaciones de IA en el reconocimiento de imágenes, el procesamiento del lenguaje natural y la generación de texto./ Modelos de lenguaje transformador, como GPT y BERT / Implementaciones de IA en la vida cotidiana, como asistentes virtuales, vehículos autónomos y sistemas de recomendación.

## ¿Qué?

||||
-|-|-|
**Modelo de lenguaje de inteligencia artificial**|*Inteligencia artificial* es un campo muy amplio que comprende diferentes técnicas, enfoques y aplicaciones. ***ChatGPT*** es una implementación específica de este campo, diseñada para comprender y generar texto.|Esta descripción es más exacta en el sentido de enfatizar que ChatGPT se especializa en el procesamiento del lenguaje natural (NLP, por sus siglas en inglés) y en la generación de texto en respuesta a las entradas del usuario.

## ¿Para qué?

|||
|-|-|
Parecer ser humano|Generar conversaciones fluidas y coherentes, responder preguntas, ofrecer recomendaciones, etc. En general, proporcionar información útil a los usuarios en una amplia gama de contextos.

## ¿Cómo?

### Casos de uso

> [📝](https://docs.google.com/presentation/d/1DeAjUGzE75wWZFIHuE7KzDVAa2DFfUJ_29sKKaL0Qwg/edit?usp=sharing)


|Caso de Uso|Descripción|Prompt(s)|
|-|-|-|
**Preguntas y Respuestas**|La  base del trabajo de ChatGPT
**Correcciones**||Corrige gramaticalmente el siguiente texto (y si no hay ningún error, dime “No hay errores”):
**Resúmenes**||Hazme un resumen de este texto…<br><br>tl;dr:
**Relevancia**||¿Cuál consideras que es la parte más importante de ese/este texto?
**Contexto**|ChatGPT tiene en cuenta el contexto|
**Propuestas de ajuste**||Reescríbelo de un modo más legible:…<br><br>Plantéame una redacción alternativa de…
**Crear pseudocódigo**|A partir de un evento conocido<br><br>A partir de un proceso descrito en prosa||
**Entender código**|A partir de un [código](https://github.com/mmasias/prg1-22-23/blob/main/temario/codigo/WhacAMole.java)|
**Traducir**||Traduce el siguiente texto a inglés…<br><hr>Traduce el siguiente texto a 1. inglés, 2. frances, 3. chino, 4. euskera…<br><hr>Supongamos las siguientes tablas y sus campos, en una base de datos de Microsoft Access:<br><br>- Empleado (id, nombre, idDepartamento)<br>- Departamento (id, nombre, direccion)<br>- Salarios (id, idEmpleado, monto, fecha)<br><br>Proponme una consulta SQL que me devuelva los nombres de los departamentos que tienen más de 10 empleados en los últimos tres meses
**Resumen estructurado**||Hazme una tabla de las frutas, indicando además color y sabor<br><br>Hay muchas frutas que se encontraron en el planeta recientemente descubierto Goocrux. Allí crecen los neoskizzles, que son de color púrpura y tienen sabor a dulce. También están los loheckles, que son una fruta de color azul grisáceo y son muy ácidos, un poco como un limón. Los pounits son de un color verde brillante y son más sabrosos que dulces. También hay muchas loopnovas que tienen un sabor rosa neón y saben a algodón de azúcar. Finalmente, existen las frutas llamadas glowls, que tienen un sabor muy ácido y amargo, que es ácido y cáustico, y un tinte naranja pálido.
**Categorización**||En qué categorías entran las siguientes empresas: Apple, Facebook, Fedex, IBM, UNEATLANTICO, MAFLOW
**Palabras clave**||Extrae las palabras clave de…
**Creación de un aviso a partir de la descripción de un producto**||Escribe un anuncio creativo para el siguiente producto que se promocionará en Facebook, dirigido a padres:<br><br>Producto: Learning Room es un entorno virtual para ayudar a los estudiantes desde preescolar hasta la escuela secundaria a destacar en sus estudios.
**Crear nombre de productos a partir de descripciones**||Propón dos o tres nombres para un producto que consiste en una máquina para hacer helados<br><br>PALABRAS CLAVE: rapidez, limpieza, ahorro de espacio<br><br>Además, si "suena" a italiano, mejor. Que no evoque la palabra “Danonino” pero que evoque el mar.
**Extender una de las propuestas**||Créame un guión de aviso publicitario para el tercer nombre que has propuesto<hr>Defiende el primer nombre que has propuesto.
**Creación de tablas / hojas de cálculo**||Hazme una tabla con cinco impresoras 3d, incluyendo nombre, fabricante y año de fabricación<hr>Dame los códigos de los aeropuertos del norte de españa en formato tabla.
**Detección de sentimientos**||Clasifica el sentimiento en estos tweets:<br><br>1. "No soporto la tarea"<br>2. "Esto es una basura. Estoy aburrido 😠"<br>3. "¡No puedo esperar para Halloween!"<br>4. "Mi gato es adorable ❤️❤️"<br>5. "Odio el chocolate"
**Extracción de información a partir de un bloque de texto**||Extrae el nombre del remitente y su dirección:<br><br>Estimada Teresa,<br>Fue genial participar en el seminario. Espero que la sesión de ChatGPT les haya resultado interesante.<br>Gracias por los enlaces. Te dejo la mi dirección de la Universidad: calle Isabel Torres 21, 39011, Santander.<br>Un saludo,<br>Manuel
**Traducciones más "abstractas"**||Dame el código CSS del color azul del cielo al atardecer<br><br>Y de un rojo opaco y fresco?<hr>(testearlo [aquí](https://www.w3schools.com/colors/colors_picker.asp))<hr>¿Y el pantone?
**Analogías**||Crea una analogía para la frase: las preguntas son como dardos
**Paráfrasis**||Reescribe el siguiente email de un modo más formal:<br>Soy Roger Wilco de la Agencia Aeroespacial del Ayuntamiento de Santander.<br>Recordarle que Larry Laffer ha sido admitido para el curso de programación que se realizará de martes 11 a viernes 14 de abril en el Centro Cívico en horario de 9:30.<br>El curso es de martes a viernes. El aula está dotada con ordenador y no hace falta que lleven ningún tipo de material<br>Roger

### GPT@Google

||Hoja de cálculo|Documento|
-|-|-|
Usando [GPT for work](https://gptforwork.com/)|Con formulas, como:<br><br>=GPT()<br>=GPT_TRANSLATE()<br>=GPT_TABLE()<br>|Desde la barra lateral

## A tener en cuenta

### Otras AI

|||
|-|-|
[Perplexity](https://www.perplexity.ai/)|Proyecto que utiliza el lenguaje natural para realizar búsquedas en la web de manera eficiente y precisa
[Stable Diffusion](https://stablediffusionweb.com/)|Modelo de difusión latente de texto a imagen capaz de generar imágenes fotorrealistas a partir de cualquier entrada de texto
[MidJourney](https://www.midjourney.com/)|El ChatGPT de la generación de imágenes
[Blue Willow](https://www.bluewillow.ai/)|Alternativa gratuita (y muy buena!) a MidJourney
[Creador imágenes Bing](https://www.bing.com/create)|Crear imágenes desde palabras con IA
[NeuroFlash](https://app.neuro-flash.com/aiWriter)|Generador de texto a partir de palabras clave
[Map Deduce](https://mapdeduce.com/)|Resumen de documentos PDF
[Slide AI](https://www.slidesai.io/es)|Creación de presentaciones

## Enlaces, bibliografía et al

- [Descripción de GPT4](https://es.wikipedia.org/wiki/GPT-4)
- [Paper con el reporte técnico de GPT4](https://arxiv.org/pdf/2303.08774)
- [**Entrevista a Sam Altman: CEO de OpenAI**](https://youtu.be/L_Guz73e6fw) 🏆 2h:30m... **¡Hay que verla entera!** ([Opinión de los Microsiervos](https://www.microsiervos.com/archivo/ia/sam-altman-openai-lex-fridman-gpt4-chatgpt-futuro-ia.html) acerca de la entrevista)
- Acerca de la explicabilidad de los algoritmos
  - [La explicabilidad](https://ignaciogavilan.com/explicabilidad-de-la-inteligencia-artificial-que-es-lo-que-queremos-explicar/)
  - [Los algoritmos sí saben explicarse](https://ignaciogavilan.com/los-algoritmos-de-inteligencia-artificial-si-saben-explicarse/)
- [Microsoft: Principios y prácticas para una IA responsable](https://learn.microsoft.com/es-es/training/paths/responsible-ai-business-principles/?WT.mc_id=academic-77998-cacaste)
- [GPT for work](https://gptforwork.com/), plugin de GPT para Google Sheet y Google Documents.

### Repos con prompts

- [Awesome ChatGPT Prompts](https://github.com/f/awesome-chatgpt-prompts)
- [En español](https://www.isocialweb.agency/prompts-espanol/)
- [Hilo de Twitter con prompts en español](https://twitter.com/IAViajero/status/1646920119698743301)
