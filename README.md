# 🏋️ Proyecto Gimnasio - CRUD con LocalStorage

## 📖 Descripción
Este repositorio contiene una aplicación web sencilla para la gestión de clientes de un gimnasio.  
Incluye funcionalidades de búsqueda, filtrado, edición inline, eliminación y persistencia de datos en `localStorage`.

---

## 🚀 Prompts utilizados

### Ejercicio 1: Diseño del dataset
vamos a crear la pagina de un gimnasio y los valores serán:
ID (número de identificación como cliente), nombre, número de teléfono,
una fecha de nacimiento, una categoría (novato, conocedor, experimentador)
y su género (hombre o mujer).

Código

### Ejercicio 2: Generación y validación con IA
Eres un generador de datos. Tu tarea es crear registros de clientes de un gimnasio siguiendo esta estructura:

Campos:

ID (numérico, único, mínimo 1)

Nombre (texto, máximo 50 caracteres)

Teléfono (numérico, 8 dígitos)

FechaNacimiento (fecha en formato YYYY-MM-DD)

Categoría (valores posibles: "novato", "conocedor", "experimentador")

Género (valores posibles: "hombre", "mujer")

Ejemplos de registros válidos:
[ ... 5 registros de ejemplo ... ]

Instrucciones:

Genera 25 registros adicionales siguiendo exactamente las mismas reglas.

No repitas IDs ni nombres.

Mantén variedad en categorías y géneros.

Asegúrate de que los teléfonos tengan 8 dígitos y las fechas estén en formato válido.

Devuelve el resultado como un array JSON.

Código

### Ejercicio 3: Visualización dinámica
ahora debemos incluir estas funcionalidades a la página pero el CSS hazlo por separado
y no muestres la información de los clientes sino que haz una interfaz que pida datos
para encontrar al usuario.

Código

Ampliación:
solo agrega que cuando encontremos al cliente muestre la información completa del cliente.

Código

### Ejercicio 4: Persistencia y CRUD
quiero que agreguemos ahora las solicitudes de la sección 4 donde agregamos persistencia
a la información agregada de un cliente creado y que pueda agregar nuevos registros del dataset
en el local storage junto con una opción para eliminar cualquier registro que deseemos en un futuro quitar.

Código

---

## ⚙️ Funcionalidades
- Dataset inicial con registros de ejemplo.
- Búsqueda y filtrado en tiempo real.
- Visualización de clientes en tarjetas.
- Edición inline de campos.
- Eliminación de registros.
- Persistencia en `localStorage`.

---

## 📂 Estructura del proyecto
/Gym
│── index.html
│── styles.css
│── README.md

