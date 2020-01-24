# senderos
Página web para realidad aumentada, para conocer los árboles de Parques Nacionales y Metropolitanos, o para realizar senderos virtuales.

Inicialmente vamos a presentar en el Parque Metropolitano La Sabana y en el Area de Conservación Isla del Coco, ambas en Costa Rica

## Uso

Visite [https://fede2cr.github.io/senderos/](https://fede2cr.github.io/senderos/)

## ¿Que es?

Es una aplicación en realidad aumentada creada como una forma moderna para acompañar a las etiquetas de identificación de especies de árbol, la cual funciona en dos modo: dentro o fuera del Parque.

### Dentro del Parque

Si su dispositivo móvil se identifica que está dentro del Parque, cuando se está cerca de árbol, lo puede señalar con la cámara para ver el nombre de la especie, información interesante y enlaces a [iNaturalist](https://www.inaturalist.org/projects/parque-metropolitano-la-sabana).

### Fuera del Parque

Si su dispositivo móvil se identifica que está fuera del Parque, en lugar de simplemente presentar un mensaje para que visite el Parque, le presenta al usuario una serie de **senderos virtuales**, los cuales corresponden en distancia a senderos reales en el Parque.

Ahora, sin importar donde se encuentre, puede comenzar a caminar y va a observar con una distancia proporcional al sendero, modelos 3D de los árboles reales, con la misma capacidad de recibir información, imágenes 360°, animaciones de especies probables a encontrar en el sendero, sonidos de pájaros, etc.

## Desarrollo

La aplicación se basa fuertemente en el ejemplo de [Click Places](https://github.com/jeromeetienne/AR.js/tree/master/aframe/examples/click-places) y el [tutorial asociado](https://medium.com/chialab-open-source/build-your-location-based-augmented-reality-web-app-c2442e716564)

### Objetivos

- Convertir sólidos de blender a formato glTF: Esto permite exportar árboles, petroglifos, sámaras (semillas voladoras), flores, esculturas y otros elementos naturales o culturales
- Reemplazar el API de Foursquare por una aplicación servidor de objetos
- Realizar ortografías y modelos 3d de varios objetos en la Sabana para demostración
- Probar una versión submarina del sendero, con ortofotografías de corales en lugar de árboles
