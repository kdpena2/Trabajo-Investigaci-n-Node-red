#  NODE-RED PARA EL DISEÑO DE DASHBOARD

****PROBLEMA:****
<p>¿Cuáles son los principales componentes que facilitan el diseño de Dashboard,su definición, uso y parámetros de configuración?</p>

****OBJETIVO GENERAL:****
<p>Identificar y describir de manera general los parámetros de configuración de los principales componentes disponibles en Node-Red para el diseño de Dashboard a través del análisis de información para su comprensión y posterior implementación.</p>

****OBJETIVOS ESPECÍFICOS:**** 
 <p><li>Identificar estudios recientes que contengan información acerca de Node-Red, para de esta forma conocer el objeto a investigar y las distintas aplicaciones en las que se encuentra, ya que puede tener en diversos campos.</li></p>
 <p><li>Comprender la funcionalidad y parámetros de configuración para el diseño de Dashboard.</li></p>
 <p><li>Desarrollar un ejemplo básico en el que se evidencie la implementación de  audio out, template, notification, chart, gauge, form dropdown.</li></p>

****ESTADO DEL ARTE****

***DESARROLLO DE PANELES DE CONTROL PARA REDES IOT BASADOS EN NODE-RED***
<p>Salvador García Jiménez.</p>
<p>En el presente estudio se plantea como objetivo  principal generar dentro de un entorno IoT (Internet of Things), el envío de contenido multimedia en directo. Para lo cual se ha planteado el uso de interfaz  de una Raspberry Pi y un módulo de cámara a la cual está conectada. Así bien el mecanismo usado para la transmisión del contenido es DASH (Dynamic Adaptive Streaming over HTTP),el cual  permite obtener  fragmentos de vídeo que facilitan la reproducción del mismo tomando en cuenta que la velocidad de reproducción dependerá de la red que se use en el momento.La cámara envia los fragmentos de video a una web. Todo este proceso se une a través  de  la herramienta Node-RED,la cual permite diseñar flujos de datos que ayudan a modificar el video a reproducir ,en adición esta cuenta con la opción a realizar un Dashboard para así interactuar con los flujos de datos que se crean.El trabajo a su vez plantea que al momento de elegir una herramienta para trabajar en IoT se debe escoger Node-Red ya que ofrece varias ventajas entre las que destacan su sencillez,facilidad de uso ,interfaz gráfica intuitiva ,disponibilidad de una comunidad de usuarios y soporte.La interfaz gráfica facilitan la comprensión del flujo de los datos ,que mediante hilos conectan diversos nodos que tienen distintos usos y aplicaciones,además, permite al usuario descargar una serie de nodos adicionales ,los cuales provienen de la antes mencionada comunidad de usuarios mismos que aportan de manera abierta sus trabajos.Esta  aplicación basada en Node.js, escrita en JavaScript y que dispone de un modelo de entradas y salidas para crear aplicaciones  permite unir dispositivos hardware, APIs y servicios online de maneras muy interesantes. Es así que al  estar basada en Node.js genera el beneficio de ser una aplicación que consume pocos recursos y por tanto pueda utilizarse en dispositivos de la gama más baja de coste como una Raspberry Pi o servicios cloud.Por otra parte,el Dashboard de Node-RED se distribuye en una especie de rejilla, cada elemento grupo tiene un tamaño, por defecto se le asigna un ancho de 6 unidades, cada una se compone de 48 píxeles. En cada grupo existen widgets, los cuales también poseen la propiedad de la anchura, por defecto será automática y ocupará la anchura del elemento. Existen diversos nodos que ofrecen una gran utilidad a la hora de combinar una interfaz gráfica de visualización de resultados con la interacción entre el usuario y el flujo de datos diseñado. Existen desde formularios, botones y listas desplegables hasta templates donde programar un fragmento de lenguaje web.Tras todo lo anterior, el vídeo se representa en un Dashboard compuesto por un flujo de datos, que a su vez se compone de distintos nodos en la plataforma Node-RED.</p>

<p>Fecha: Valencia, 3 de diciembre de 2018.</p>

<p>Al igual que en este estudio al momento de diseñar Dashboard en node-red se pudo constatar sus ventajas ,ya que enfocándonos  en la interfaz gráfica que ofrece este ,se logró  comprender de manera clara cómo fluyen los datos,cuya transmisión se lleva a cabo mediante una especie de cajas llamadas nodos conectadas por hilos, las cuales pueden generar distintos usos .Además ,se incluye dentro del estudio como de la investigación que realizamos los principales widgets del Dashboard que permiten configurarlos a beneficio del usuario.</p>


***SISTEMA DE MONITOREO DE CALIDAD DEL AIRE BASADO EN MQTT USANDO NODE MCU Y NODE-RED***

<p>Somphop Chanthakit,Choopan Rattanapoka.</p>
<p>Colegio de Tecnología Industrial, Universidad de Tecnología del Rey Mongkut.</p> <p>Bangkok del Norte, Bangkok, Tailandia.</p>

<p>El documento se enfoca en la implementación de un  sistema de monitoreo de calidad del aire basado en MQTT. Este  dispositivo que mide la calidad del aire  no es más que  un hardware basado en ESP8266 NodeMCU que se conecta con varios sensores los cuales a su vez miden la  temperatura, humedad, concentración de monóxido de carbono y gas de ozono .En este caso se hace uso de  Node-RED como un suscriptor que se suscribe para recibir  los datos enviados  desde el  MQTT Broker. Se opta por este tipo de herramienta ya que se señala que node-Red es una herramienta de desarrollo que se centra  en el  flujo de los datos y la cual  a su vez fue desarrollada originalmente por IBM para el cableado de dispositivos de hardware, API y servicios en línea como parte de Internet de las cosas, genera y pone a disposición del usuario un editor de flujo basado en navegador, que puede ser usado para crear funciones de JavaScript.Además cuenta con la ventaja de que las aplicaciones  que se hayan realizado anteriormente se pueden guardar o compartir para su reutilización.Por tanto con Node-RED, se realiza fácilmente un flujo para administrar y manejar los datos recibidos. Node-RED cuenta con un panel de control de calidad del aire,al sula se le envía los datos, que es una aplicación web receptiva usada para mostrar datos en la interfaz de usuario de indicadores, texto y gráficos. Incluso cuando el valor de algunos datos excede el rango configurado, Node-RED enviará un mensaje de alarma a través de LINE Notify para notificar a los usuarios.</p>

</p>Para este estudio el panel de control de calidad del aire ,muestra tres tipos de interfaz de usuario desde datos de cada sensor (indicador, texto y gráfico). Finalmente como se menciona anteriormente el tablero es una aplicación web receptiva, por lo que puede ser mostrada  perfectamente en un teléfono móvil o en la web.</p>

<p>Fecha de la conferencia: 11-13 de julio de 2018.</p>
<p>Fecha añadida a IEEE Xplore : 08 de noviembre de 2018.</p>
 
<p>En el caso de nuestro trabajo al igual que en la investigación se pude visualizar que la interfaz gráfica que nos ofrece node-red constituye un entorno agradable para que el usuario desarrolle su trabajo,además, una vez más se evidencia la clara ventaja de sencillez al momento de entender cómo fluyen los datos  ,en el caso del estudio se usado los widgets disponibles en dashboard como el texto, indicador y gráfico ;mismos que hemos utilizado en los programas en adición con otros como la salida de audio como en el caso del velocímetro o aquel que  guarda claves en una base de datos.</p>


****MARCO TEÓRICO****

***¿Qué es un dashboard en Node-Red?***


<p>El diseño del dashboard debe considerarse como una cuadrícula. Cada elemento del grupo tiene un ancho: de forma predeterminada, 6 ‘unidades’ (una unidad tiene 48 píxeles de ancho de forma predeterminada con un espacio de 6 píxeles).</p>
<p>Cada widget del grupo también tiene un ancho: de forma predeterminada, ‘auto’, lo que significa que ocupará el ancho del grupo en el que se encuentra, pero puede establecerlo en un número fijo de unidades.</p>
<p>El algoritmo de diseño del tablero siempre trata de colocar elementos tan altos y a la izquierda como sea posible dentro de su contenedor; esto se aplica a cómo se posicionan los grupos en la página, así como a cómo se colocan los widgets en un grupo.</p>
<p>Dado un grupo con un ancho de 6, si agrega seis widgets, cada uno con un ancho de 2, se colocarán en dos filas, tres widgets en cada uno.</p>
<p>Si agrega dos grupos de ancho 6, siempre que la ventana de su navegador sea lo suficientemente ancha, se sentarán uno al lado del otro. Si encoge el navegador, en algún momento el segundo grupo cambiará para estar debajo del primero, en una columna.</p>
<p>Es posible utilizar múltiples grupos si es posible, en lugar de un gran grupo, para que la página pueda cambiar de tamaño dinámicamente en pantallas más pequeñas.</p>

***Nodos principales del dashboard*** 

<p>Es importante mencionar que en varios de los nodos van a existir los parámetros:</p>
<p><li>Group/ grupo: Aquí se va a contener el nodo dentro del dashboard, si se va a implementar distintos nodos para un mismo objetivo, lo mejor sería colocarlos en el mismo grupo.</li></p>
 
<p><li>Label/ Etiqueta: Se asigna el nombre que va a tener cada uno de los nodos al ser mostrados.</li></p>
<p><li>Tooltip/ Información sobre herramientas: Se escribe una indicación al usuario, esta aparecerá al acercar el cursor al componente.</li></p>
 
![](https://github.com/kdpena2/Trabajo-Investigaci-n-Node-red/blob/master/IMG/Imagen1.png)

<p><li>Name: Se sitúa el nombre que se va a visualizar solo en la terminal.</li></p>
 
***Button:***
<p>Agrega un botón a la interfaz del usuario, el cual al ser presionado debe dar como resultado lo que se indique.</p>
<p><li>Payload: Se coloca lo que se devuelve al dar click en el botón, estos datos pueden ser de tipo string, number, boolen, JSON, buffer, timestamp, flow, global.</li></p>
 
 
![](https://github.com/kdpena2/Trabajo-Investigaci-n-Node-red/blob/master/IMG/Imagen%202.png)

***Dropdown:***
<p>Agrega un cuadro desplegable a la interfaz del usuario.</p>
 
<p><li>Placeholder/Marcador de posición : Se escribe un texto que indique lo que debe seleccionar entre las opciones. También es posible escoger si se puede responder una sola opción o todas.</li></p>
<p><li>Options: En el primer recuadro se agrega el tipo de dato que se va a ingresar, puede ser de tipo number, string o boolen, se añade el número de opciones que se quiera y en label se ingresa la opción.</li></p>

 ![](https://github.com/kdpena2/Trabajo-Investigaci-n-Node-red/blob/master/IMG/Imagen3.png)

***Switch:***
<p>Agrega un interruptor a la interfaz del usuario. </p>
<p><li>On payload/ en carga útil: Incluye dos botones en su configuración, los cuales van a retornar dos estados en caso de ser presionados, estos estados al igual que los botones pueden ser de tipo entero, string, boolean, y entre otros ya antes mencionados.</li></p>

 ![](https://github.com/kdpena2/Trabajo-Investigaci-n-Node-red/blob/master/IMG/Imagen%204.png)
 

***Slider:***
<p>Agrega un control deslizante manipulable a la interfaz de usuario. Una de sus aplicaciones  se puede observar conectado a un gauge, el cual es un widget de tipo indicador que se agrega a la interfaz del usuario. Con el deslizante se puede observar cómo se va a mover el indicador del gauge. </p>
 
<p><li>Range: Se define el inicio, fin y paso que va a tener el nodo. Una de las particularidades en node red, es que el nodo slider puede conectarse al texto y devolver valores, transformado los datos de string a entero.</li></p>
<p><li>Output: Se puede seleccionar si se quiere que se muestre en la terminal el valor en el que se quedó el deslizador en la interfaz.</li></p>
 
 ![](https://github.com/kdpena2/Trabajo-Investigaci-n-Node-red/blob/master/IMG/Imagen%205.png)
 

***Numeric:***
<p>Agrega un widget de entrada numérico a la interfaz de usuario.</p>
 
<p><li>Range/ Rango: Se pone el valor de inicio y fin que será seleccionado por medio de flechas. </li></p>
<p>Si se quiere que una vez llegado al número final se retorna al inicio marcar Valor de ajuste de max a min y min a max.</p>

 ![](https://github.com/kdpena2/Trabajo-Investigaci-n-Node-red/blob/master/IMG/Imagen%206.png)
  

***Text imput:***
<p>Agrega un campo de entrada de texto a la interfaz del usuario, el cual puede tener distintos modos.</p>
<p><li>Label: Se coloca lo que se quiere que el usuario ingrese, y se puede visualizar con el nodo text.</li></p>

<p><li>Mode: Aquí se selecciona el tipo de entrada, la cual puede ser de texto, dirección de email, contraseña, número, teléfono, selector de color, selector de tiempo, selección de semana y mes. </li></p>

![](https://github.com/kdpena2/Trabajo-Investigaci-n-Node-red/blob/master/IMG/Imagen%207.png)

***Date picker:***
<p>Agrega un widget de selector de fecha a la interfaz del usuario.</p>
 
![](https://github.com/kdpena2/Trabajo-Investigaci-n-Node-red/blob/master/IMG/Imagen%208.png)

***Colour picker:***
<p>Agrega un selector de color al tablero.</p>
 
<p><li>Format: Se puede escoger entre hx, hx8, hsl, hsv, rgb.</li></p>
 
<p><li>Send: Aquí se puede seleccionar entre enviar múltiples valores durante la edición o un valor cuando se haya cerrado.</li></p>
<p><li>Playload: Existen dos opciones, la primera es devolver el valor actual como objeto, o como una cadena.</li></p>
 
![](https://github.com/kdpena2/Trabajo-Investigaci-n-Node-red/blob/master/IMG/Imagen%209.png)


***Form:***
<p>Agrega un formulario a la interfaz del usuario.</p>

<p><li>Form elements: Se muestra una serie de elementos a ingresar, se escoge el tipo que puede ser: texto, multilínea, número, e-mail, contraseña, switch o fecha. También se puede seleccionar si es o no requerido el ingreso de este elemento.</li></p>

<p><li>Buttons: Se muestran dos opciones después de haber ingresado lo que se pide en form elements.</li></p>

![](https://github.com/kdpena2/Trabajo-Investigaci-n-Node-red/blob/master/IMG/Imagen%2010.png)


***Text:***
<p>El componente text es una salida de texto que sirve para mostrar un campo de texto no editable en la interfaz.</p>
<p><li>Label/ Etiqueta: colocamos lo que queremos que nos aparezca en la pantalla, y en el diseño se puede escoger entre las opciones que se encuentran.</li></p>

![](https://github.com/kdpena2/Trabajo-Investigaci-n-Node-red/blob/master/IMG/Imagen%2011.png)


***Chart:***
 
![](https://github.com/kdpena2/Trabajo-Investigaci-n-Node-red/blob/master/IMG/Imagen%2012.png)

<p>Este nodo agrega un gráfico al tablero. El gráfico utiliza valores enviados a través de msg.payload para su visualización. Los gráficos admiten hasta nueve series diferentes de valores.Tiene modos de línea, barra y gráfico circular. Además, las etiquetas del eje X se pueden personalizar utilizando una cadena de formateador de fecha. El gráfico a su vez utiliza valores enviados a través de msg.payload para su visualización. Los gráficos admiten hasta nueve series diferentes de valores.</p>

![](https://github.com/kdpena2/Trabajo-Investigaci-n-Node-red/blob/master/IMG/Imagen%2013.png)

<p>Se puede elegir el tipo diseño entre dos opciones,es decir,que este puede ser lineal o radial.</p>
<p><li>Modo: Opción para activar el modo diferencial. Con esta opción seleccionada, la pista coloreada tiene un punto central desde el cual se muestra el valor. El valor del punto central se puede ajustar. Si el valor central no está definido, el punto central está exactamente entre el mínimo configurado y el máximo.</li></p>
<p><li>Label/ Etiqueta: Se asigna el nombre que va a tener cada uno de los nodos al ser mostrados en la pantalla.</li></p>
<p><li>Color de la pista: Se puede configurar el color de la línea de fondo de la pista. Por defecto, los colores del sitio utilizados.</li></p>
<p><li>Marcas de verificación: Los valores mínimos y máximos se pueden mostrar cerca de la pista. Para el modo diferencial, también se muestra el valor central. Con el diseño radial, las marcas de verificación solo se pueden mostrar si el tamaño del diseño es de 3x3 unidades o más.</li></p>
<p><li>Unidad: La unidad se muestra cerca del campo de valor. La unidad puede ser cualquier cadena.</li></p>
<p><li>Decimales: El valor siempre se redondea según los decimales configurados. El valor predeterminado es cero, por lo que el valor se presenta como entero.</li></p>

<p><li>x-axis and y-axis: Las coordenadas x / y del nodo cuando se dibuja el flujo.</li></p>
 
 ***Audio out:***
 
![](https://github.com/kdpena2/Trabajo-Investigaci-n-Node-red/blob/master/IMG/Imagen%2014.png)


<p>Un widget que le permitirá reproducir audio (wav o mp3) o enviar texto a voz (TTS) al cliente.Este nodo reproducirá audio de texto a voz de los mensajes enviados a través del objeto msg.payload . El audio se reproducirá incluso cuando el tablero esté minimizado.</p>

 
![](https://github.com/kdpena2/Trabajo-Investigaci-n-Node-red/blob/master/IMG/Imagen%2015.png)

<p><li>Group/Grupo:Es el espacio en el que se va a contener el nodo dentro del dashboard.</li></p>
<p><li>TTS Voice:TTS estas siglas significan text to speech ,es decir, texto para hablar.Esta opción envía una cadena de texto al motor de texto a voz de Google para que se convierta en audio de voz. El servicio TTS de Google tiene un límite de longitud de cadena de entrada de 200 caracteres. Si el texto a traducir tiene más de 200 caracteres, se dividirá de manera inteligente en segmentos y la salida consistirá en una matriz de URL que se vinculan a archivos de audio secuencias que codifican cada segmento.</li></p>
<p><li>Name/Nombre:Será el identificativo para reconocer a  ese widget.</li></p>
 
***Notification:***
 
![](https://github.com/kdpena2/Trabajo-Investigaci-n-Node-red/blob/master/IMG/Imagen%2016.png)


<p>La notificación , que crea alertas para el usuario, puede ser una ventana emergente de pan tostado o un cuadro de alerta descartable. La alerta puede estar dirigida a un solo usuario.Para que en el Dashboard quede constancia de todos las acciones realizadas , mediante las notificaciones de Node-Red , salen unos avisos en el lado derecho arriba sobre las acciones pulsadas o realizadas en cada momento.Es decir que este nodo muestra notificaciones como ventanas emergentes en la interfaz del tablero. msg.payload será el mensaje emergente, msg.topic será el título y msg.highlight establecerá el color de resaltado del borde opcional.</p>

![](https://github.com/kdpena2/Trabajo-Investigaci-n-Node-red/blob/master/IMG/Imagen%2017.png)

<p><li>Layout/Diseño:Se refiere a la parte en la que se presentará la notificación.</li></p>

<p><li>Timeout/Tiempo de salida:Tiempo que será mostrado el mensaje en el dashboard.</li></p>
<p><li>Border/Borde:Hace referencia al borde del recuadro de notificación.</li></p>
<p><li>Topic/Tema:se selecciona el tema que puede ser opcional.</li></p>
<p><li>Name:Será  el identificador con el que se reconocerá.</li></p>
 
***Template:***

<p>El nodo de plantilla permite al usuario especificar y crear sus propios widgets dentro del marco utilizando HTML, Javascript. Este es un widget Angular.js. También puede usar esto para anular los estilos CSS incorporados.</p>
<p>Hay dos nodos de plantilla en nodo-rojo. Son el nodo de plantilla HTML y el nodo de plantilla de panel.</p>
Las propiedades del nodo de plantilla se muestran a continuación.</p>

![](https://github.com/kdpena2/Trabajo-Investigaci-n-Node-red/blob/master/IMG/Imagen%2018.png)

<p>El nodo acepta entradas en el objeto msg.payload.</p>
<p>El campo llamado propiedad establece el nombre del objeto de salida del nodo.</p>
<p>Normalmente esto es msg.payload pero puede cambiarlo a lo que quiera. por ejemplo, msg.options. Incluso puede enviarlo directamente a un flujo o variable global.</p>

![](https://github.com/kdpena2/Trabajo-Investigaci-n-Node-red/blob/master/IMG/Imagen%2019.png)

<p>Si la plantilla contiene datos JSON o datos YAML , lo cual es común cuando se usa la plantilla como un nodo de configuración, puede generar los datos como un objeto JSON analizado o un objeto YAML analizado, es decir, JavaScript .</p>

![](https://github.com/kdpena2/Trabajo-Investigaci-n-Node-red/blob/master/IMG/Imagen%2020.png)

<p><li>Template type:se refiere a en qué grupo se encuentra este widget.</li></p>
<p><li>Group/ grupo: Aquí se va a contener el nodo dentro del dashboard, si se va a implementar distintos nodos para un mismo objetivo.</li></p>
<p><li>Size:Dirá la medida que puede ser elegida por el usuario, caso contrario permanecerá con la medida autodesignada.</li></p>
 
***Gauge:***

<p>Este nodo muestra un widget de tipo de indicador en el tablero. Formateará los números pasados a través de msg.payload en un widget de estilo de indicador. El medidor contiene diferentes sectores y la aguja se moverá a diferentes sectores según el Rango y el valor pasado al widget a través de msg.payload.</p>
 
![](https://github.com/kdpena2/Trabajo-Investigaci-n-Node-red/blob/master/IMG/Imagen%2021.png)

<p><li>Group/ grupo: Aquí se va a contener el nodo dentro del dashboard, si se va a implementar distintos nodos para un mismo objetivo, lo mejor sería colocarlos en el mismo grupo.</li></p>
<p><li>Size:Se selecciona el tamaño del gráfico.</li></p>
<p><li>-Type/tipo: Selecciona el tipo de gráfico a mostrar.Tiene 4 modos: estándar (calibre simple), rosquilla (completa 360 °), brújula y onda. También puede especificar la gama de colores de los medidores estándar y de rosquilla.</li></p>
<p><li>Label/ Etiqueta: Se asigna el nombre que va a tener cada uno de los nodos al ser mostrados en la pantalla.</li></p>
<p><li>Rango: Configure los valores mínimos y máximos esperados y ajuste el color de la línea. Agregue segmentos y configure colores para ellos si es necesario. Tenga en cuenta que las opciones MIN y MAX no se pueden eliminar. Se puede dibujar un pequeño punto con color de segmento en el punto del segmento. Para mostrar el punto por segmento, configure el tamaño para el punto mayor que cero.</li></p>
 
<p><li>Unidad:se muestra cerca del campo de valor. La unidad puede ser cualquier cadena.</li></p>
<p><li>Sectors:Pueden variar conforme datos numéricos.</li></p>
<p><li>Colour gradient:En esta opción podemos modificar el color a visualizar en el tipo de gráfico seleccionado.</li></p>

****DIAGRAMAS****

***Diagrama de caso uso del programa “audio output”***

<p>Este diagrama expresa la relación entre humano y máquina que existe en el momento de interpretar la información del usuario sea por entrada de teclado o por botón la máquina analiza el contenido y devuelve una salida de audio. </p>

![](https://github.com/kdpena2/Trabajo-Investigaci-n-Node-red/blob/master/IMG/Imagen%2022.png)

***Diagrama de flujo del programa “Char / Gauge / Notificación”***
 
<p>Para este diagrama expresamos el retraso con el cual se va a generar los números aleatorios y en cómo se van a ver expresados  en sus gráficos de char y gauge cabe recalcar que la generación de número es consecutiva. </p>
 
 ![](https://github.com/kdpena2/Trabajo-Investigaci-n-Node-red/blob/master/IMG/Imagen%2023.png)


****LISTA DE COMPONENTES****
<p>Estos son los recursos que se han utilizado a lo largo del desarrollo del trabajo de investigación.</p>

![](https://github.com/kdpena2/Trabajo-Investigaci-n-Node-red/blob/master/IMG/Imagen%2024.png)


****MAPA DE VARIABLES****

***ran***

<p>Crea un espacio de memoria con el cual guardamos el número aleatorio que vamos a generar para el programa de char/gauge</p>

***msg***

<p>Crea un espacio de memoria con el cual ingresamos la cadena de caracteres para el programa audio output</p>

***text***
<p>crea un espacio de memoria que nos permite reemplazar el valor de la cadena de texto por un espacio vacío o por el botón que sigue en el programa audio output.</p>


****EXPLICACIÓN DE CÓDIGO FUENTE****

***Explicación codigo “Audio Output”***

<p> Como primer punto usamos el nodo inject para inicializar nuestra variable msg a usar, conectado a este irá el nodo input en el cual podremos ingresar texto para que el programa lo procese, anterior a este usamos una conección entre un nodo delay y un nodo function con los cuales podremos generar un retraso, estos permitirán que  nuestra variable ingresada en el nodo input  se limpie mediante una codificación en JS. </p>

<p>text=msg.playload;</p> 
<p>if(text !== ""){</p>
    <p>msg.playload = "";</p>
   <p> return msg;</p>
<p>}</p>
<p>y le otorgue espacio espacio para poder escribir otra cadena de texto, consecuente a esto conectamos un nuevo nodo function el cual cambiará la palabra antigua por la nueva.</p>
<p>text=msg.playload;</p>
<p>if(text !== ""){</p>
  <p>  msg.playload = text;</p>
   <p> return msg;</p>
<p>}</p>
<p>Un nodo de salida de audio estará conectado al final de este para poder escuchar la palabra impuesta, con el método base establecido empleamos nodos button para que mediante un link se conecten al nodo input y de esta manera tener palabras preestablecidas alojadas dentro del botón por último conectamos un nodo notification el cual nos permite a la par que escuchamos la palabra visualizarla como si de un mensaje se tratara.</p>

***Explicación codigo “Char / Gauge / Notification”***

<p>Mediante un nodo inject inicializamos nuestra variable msg que node red usa por defecto al mismo tiempo que le incluimos un intervalo de 2 segundo este nodo lo conectaremos a un nodo function en el cual crearemos nuestro número aleatorio </p>
<p>ran =parseInt(Math.random() *10);</p>
<p>msg.topic = "Random1";</p>
<p>msg.payload = ran;</p>
<p>return msg;</p>
<p>El cual nos servirá como base para nuestro nodo char y nuestros nodos gauge los cuales genera gráficos en un espacio x, y con un intervalo de 2 segundos establecidos anteriormente el mismo método lo usamos para generar un número aleatorio que lo muestre un nodo notification. </p>

***Explicación código “Forms”***

<p> Usamos directamente el nodo forms el cual irá conectado a un nodo debug el cual revisa errores el nodo forms es configurable y en este podemos ingresar datos por teclado podemos decidir cuántos valores ingresar, si estos valores son obligatorios o no para la persona que ejecuten el programa y descargando un nodo cloudant mediante escribir npm install node-red-node-cf-cloudant en la consola de node-Js podremos usar una base de datos que la generemos con anterioridad por ejemplo en IBM cloud.</p>

***Explicación código “Template”***

<p>Para el uso el nodo template basta con conectarlo a un nodo inject una vez conectado el nodo template nos otorga de un espacio programable con estructura HTML en el cual podemos programar de forma libre el espacio y llenarlo de nuestra información en nuestro caso se genera una plantilla basado en estructura JS y CSS llamando a los lenguajes mediante las etiquetas <script> y <syle> respectivamente. </p>

****DESCRIPCIÓN DE PRERREQUISITOS Y CONFIGURACIÓN****

![](https://github.com/kdpena2/Trabajo-Investigaci-n-Node-red/blob/master/IMG/Imagen%2026.png)

****APORTACIONES****

<p> Para la implementación de los programas solicitados se agrego el uso de nodos diferentes como  botones, links y funciones los cuales permitieron generar una interfaz más interactiva con el usuario de la misma manera se propuso  una plantilla para llenar el nodo template basado en una estructura de etiquetado HTML con la ayuda de etiquetas Style y Script para mostrar una plantilla agradable.</p>

****CONCLUSIONES****

<p><li>Node-Red brinda una interfaz gráfica amigable con el  usuario,para el desarrollo y diseño de Dashboard,ya que cuenta con distintos widgets los cuales han sido definidos a lo largo de la investigación conforme lo planteado,a su vez se revisó los parámetros de configuración de cada uno.</li></p>
<p><li>La herramienta de Node-red es muy potente ya que sirve para comunicar hardware y servicios de una forma muy rápida y sencilla. Además simplifica de gran manera la tarea de programar gracias a la programación visual.</li></p>
<p><li>Se cumplió nuestro objetivo acerca de desarrollar ejemplos básicos donde se evidencie el uso del dashboard de Node-red , esto debido a las investigaciones realizadas referentes al uso de la herramienta de programación, su funcionamiento y características. </li></p>

****RECOMENDACIONES****

<p> Se recomienda que antes de intentar generar una interfaz el usuario cuente con la instalación de todos los nodos posibles si va usar una base de datos instalar el nodo cloudant o si va a usar una salida de audio con voz en español descargar el nodo play audio. </p> 
<p>Es recomendable conocer los parámetros de configuración de cada nodo a fin de evitar fallas en el desarrollo de los programas.</p>

****CRONOGRAMA****

![](https://github.com/kdpena2/Trabajo-Investigaci-n-Node-red/blob/master/IMG/Cronograma.png)

 
****BIBLIOGRAFÍA****

<p>García Jiménez, S. (2019). Desarrollo de paneles de control para redes IoT basados en NodeRed (Doctoral dissertation).</p>
<p>S. Chanthakit and C. Rattanapoka, "MQTT Based Air Quality Monitoring System using Node MCU and Node-RED," 2018 Seventh ICT International Student Project Conference (ICT-ISPC), Nakhonpathom, 2018, pp. 1-5, doi: 10.1109/ICT-ISPC.2018.8523891.</p>
<p>(20 de 11 de 2018). Obtenido de Aprendiendo Arduino: https://aprendiendoarduino.wordpress.com/2018/11/20/node-red/</p>
<p>OpenJS Foundation. (s.f.). Node-red. Obtenido de Node-red: https://nodered.org</p>
<p>OpenJS Foundation. (Julio de 2020). Node-RED. Obtenido de https://flows.nodered.org/node/node-red-dashboard</p>

****ANEXOS****

![](https://github.com/kdpena2/Trabajo-Investigaci-n-Node-red/blob/master/ANEXOS/ANEXO%201.png)



![](https://github.com/kdpena2/Trabajo-Investigaci-n-Node-red/blob/master/ANEXOS/ANEXO%202.png)








