# Electrónica IV 2023. Trabajo Práctico 3. Controlador de luz de escalera

**Aquí hay que copiar la especificación del proyecto y formatear(??. Y describir cómo será el proyecto. Diseño general, implementación, patitas del micro. Usaremos el led del bluepill para ahorrar en componentes, en cualquier patita podemos colocar los pulsadores**
Hay dos opciones:
1) Podemos usar una organización modular donde vamos a tener varios archivos C y podemos mantener todos los archivos en SRC
2) Separar el proyecto en un programa principal que va a estar en src que es donde va a estar definido main y librerias propias que las crearemos como subcarpetas de lib
SUGERENCIA: Comenzar a hacer todo en src y despues ir moviendo las cosas a libreria.
Si implementamos pruebas de software el codigo que se prueba se pone normalmente en libreria.
En test se ponen como subcarpetas de test los conjuntos de prueba y un archivo de configuracion para decirle al micro cómo entregar los resultados. No lo usamos por ahora.
OBS: Platform.ini tiene poco texto porque aun no está configurado el emulador, directamente está configurada la plataforma.
Antes de crear el repositorio hay que crear un archivo que se llame readme.md  , aqui ponemos 
md=markdown es un formato que permite escribir texto estructurado con encabezado, imagenes, etc, como texto plano con códigos especiales:
1 numeral # indica un encabezado de primer nivel, es decir el mas grande
2 numeral ## encabezado de segundo nivel, ### de tercer nivel, etc.
**En negrita
*Inclinado
Se separan los párrafos con una línea "blanca".
//Por ahora guardamos el archivo en el repositorio: 
Source control: Publish to github