# AluraGeek

![AluraGeek Screenshot](https://github.com/user-attachments/assets/3fc0f65a-f476-4e31-b7a7-ac16b66e6833)

**AluraGeek** es una aplicación web desarrollada por **Mauro Heinrich** que permite gestionar una lista de productos con operaciones completas **CRUD** (Crear, Leer, Actualizar, Eliminar). Es ideal para practicar habilidades de frontend y backend con tecnologías modernas.

## 🧩 Descripción

La aplicación está diseñada para ser intuitiva y funcional, permitiendo a los usuarios:

- **Visualizar** productos en un catálogo dinámico.
- **Agregar** productos proporcionando detalles como nombre, precio e imagen.
- **Eliminar** productos fácilmente desde el catálogo.
- Actualizar la interfaz en tiempo real utilizando el manejo dinámico del DOM.
- Realizar todas las operaciones en un servidor simulado con **json-server**.

## ✨ Características Destacadas

- Interfaz amigable basada en HTML5 y CSS3.
- Uso de **JavaScript moderno (ES6)** para manejar la lógica.
- **json-server** para simular una API RESTful.
- Implementación de buenas prácticas como **BEM** en los estilos CSS.
- Uso de la **Fetch API** para realizar solicitudes HTTP asíncronas.

## 💻 Tecnologías Utilizadas

- **HTML5** y **CSS3**: Diseño y estructura visual.
- **JavaScript (ES6)**: Interactividad y lógica de negocio.
- **json-server**: API RESTful para operaciones CRUD simuladas.
- **Node.js y npm**: Gestión del entorno de desarrollo y dependencias.
- **BEM**: Organización y mantenibilidad de los estilos CSS.

## 🚀 Instalación y Configuración

### Requisitos previos

- Tener instalado **Node.js** (versión 16 o superior).
- Navegador web moderno compatible con ES6.

### Pasos de instalación

1. Clonar este repositorio:

   ```bash
   git clone https://github.com/mauroheinrich/alurageek.git
2. Cambiar al directorio del proyecto:

cd alurageek

3. Instalar las dependencias del proyecto:
npm install

4. Iniciar el servidor simulado:

npm start

5. Abrir el archivo index.html en el navegador para ver la aplicación.

📂 Estructura del Proyecto
El proyecto sigue una estructura organizada para facilitar su mantenimiento:

index.html: Archivo principal de la interfaz de usuario.
styles/:
reset.css: Normalización de estilos.
style.css: Estilos personalizados para la aplicación.
js/:
controllers/main.js: Controlador principal que gestiona eventos y acciones del usuario.
services/product-services.js: Funciones para interactuar con el servidor simulado (GET, POST, DELETE).
db.json: Base de datos simulada utilizada por json-server.
package.json: Dependencias y scripts configurados para el entorno Node.js.
🌐 Rutas de la API Simulada
El proyecto utiliza json-server para gestionar una API RESTful con las siguientes rutas:

GET /products: Devuelve todos los productos.
POST /products: Agrega un nuevo producto.
DELETE /products/:id: Elimina un producto específico.
Configuración adicional
Si necesitas cambiar la URL base del servidor, asegúrate de editar el archivo product-services.js.

🛠️ Uso de la Aplicación
Visualizar Productos: Al cargar la página, los productos se obtienen automáticamente desde la API simulada.
Agregar Producto:
Rellena el formulario con el nombre, precio y URL de la imagen.
Haz clic en el botón Enviar para agregar el producto.
Eliminar Producto:
Haz clic en el ícono de la papelera en cualquier producto para eliminarlo.
📈 Próximas Mejoras
Implementación de funcionalidad de edición para productos existentes.
Validación avanzada en los formularios de entrada.
Filtrado y búsqueda de productos.
Desarrollado con ❤️ por Mauro Heinrich. Para consultas o colaboración, no dudes en contactarme en mis redes sociales o GitHub.