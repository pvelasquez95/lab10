# frontend
Implementación de ReactJS

### Definición general
- El sitio funciona como una pantalla única sobre la cual se muestran todos los elementos manejados (videojuegos) y las respectivas operaciones CRUD para su manejo.
- Se manejo un archivo CSS con toda la parte visual del sitio, esto incluyendo el titulo con una animación de transición de colores y el manejo de animaciones para el efecto hover sobre cada carta. También se utilizar para manejo de colores generales y fuentes del sitio y los modal respectivos.

### Componentes
- Se utilizó nginx para su uso en docker
- Se utilizó bootstrap para generar una página responsive
- Se utilizó redis para el manejo de cache

### Explicación en nube
- Tras levantar el backend en nube se tuvo que realizar modificaciones en el código para apuntar ahora hacia el load balancer de la nube.
- Todos los servicios se encuentran funcionando desde la nube de AWS.
- El frontend cuenta con un autoscaling group que permite que la instancia se levante a si misma si se produce algún problema.

