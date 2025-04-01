# Registro de Notas con Web Storage

## Descripción
Este proyecto es una aplicación web sencilla de registro de notas que utiliza **Web Storage** para almacenar información del usuario. Implementa **LocalStorage**, **SessionStorage** y **Cookies** para mejorar la experiencia del usuario y permitir la persistencia de datos.

## Tecnologías utilizadas
- **HTML5** para la estructura de la página.
- **CSS3** para el diseño y estilos.
- **JavaScript** para la funcionalidad e interacción con Web Storage.

## Características
1. **Añadir notas:** El usuario puede agregar nombres de estudiantes con sus respectivas notas.
2. **Eliminar notas:** Cada nota tiene un botón para ser eliminada individualmente.
3. **Persistencia con LocalStorage:** Las notas se guardan en LocalStorage para que permanezcan después de recargar la página.
4. **Contador de sesión con SessionStorage:** Se cuenta el número de accesos en la sesión actual.
5. **Personalización con Cookies:** Se solicita y almacena el nombre del usuario para mostrar un saludo personalizado.

## Instrucciones de uso
1. Abre el archivo `index.html` en un navegador web.
2. Ingresa tu nombre cuando se te solicite (este se almacenará en una cookie por 7 días).
3. Agrega registros de notas ingresando el nombre del estudiante y la calificación en los campos de texto, luego presiona el botón **Agregar**.
4. Observa cómo las notas se almacenan y persisten tras recargar la página.
5. Para eliminar una nota, haz clic en la **X** junto al registro correspondiente.
6. Revisa el contador de accesos en la sesión actual.

## Estructura del Proyecto
```
/WebStorageNotas
│── index.html  # Página principal con la funcionalidad
│── styles.css  # (Opcional) Archivo de estilos CSS
│── script.js   # (Opcional) Archivo separado de JavaScript
```

## Autor
Desarrollado como práctica educativa para el aprendizaje de Web Storage y manipulación del DOM en JavaScript.

## Licencia
Este proyecto es de código abierto y puede ser utilizado con fines educativos y de aprendizaje.