
OBJETIVO DEL PROYECTO

La aplicación desarrollada ofrece al usuario la posibilidad de registrar sus actividades deportivas, controlar su peso  y marcarse objetivos a alcanzar.
La aplicación presentará en diferentes gráficas la evolución de sus actividades, ofreciendo información de tiempo, distancia recorrida, velocidad, calorías e irá animando al usuario a mejorar sus marcas y alcanzar sus objetivos.
También mostrará la evolución de su peso y calculará en función de su edad, estatura y sexo, los niveles de peso recomendados por la OMS proponiéndole hábitos saludables para ayudarle a mantenerse en forma. 

En el transcurso del proyecto se han desarrollando las funcionalidades principales de la aplicación:
Recogida de datos, introducción de los mismos en bases SQL mediante tablas y recuperación, procesamiento y representación de los mismos en gráficas e índices.
Falta por implementar los Try & Catch Exceptions para recoger los casos en los que si el usuario no mete todos los datos necesarios para los cálculos y representación,  aparezca un mensaje que le indique que hay datos aun por especificar y la aplicación no se cierre.

Por ello la aplicación en la versión actual necesita desde la primera pantalla inicial y antes de navegar por las Tabs que se introduzcan:
•	Los datos del usuario: 
		Nombre, fecha nacimiento, altura, sexo y peso objetivo.
•	Al menos dos entrenamientos de cada actividad
		Tiempo, distancia y fecha en el calendario del mes y año en curso
		en Run, Swim, Bike y Gym.
•	Al menos dos datos de peso en distintas fechas en el calendario del mes y año en curso

Ha quedado por implementar además de toda la captura de excepciones en los casos de datos nulos, las funcionalidades para filtrar:
	Datos de la gráfica de entrenamientos 
		por actividades, tiempos, distancias, calorías
	Periodo de tiempo a mostrar
		en semanas, meses, años…
Estos filtros de tiempo también se aplicarían a la última gráfica de pesos.
