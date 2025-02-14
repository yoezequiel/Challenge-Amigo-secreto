# 🎁 Amigo Secreto

Este proyecto es una aplicación web simple para gestionar un sorteo de **Amigo Secreto**. Permite a los usuarios agregar nombres a una lista, visualizarla y realizar un sorteo aleatorio para seleccionar un nombre.

## 📝 Características

- **Agregar amigos:** Los usuarios pueden añadir nombres a la lista.
- **Visualización de la lista:** Los nombres añadidos se muestran dinámicamente en la interfaz.
- **Sorteo aleatorio:** Un nombre de la lista se selecciona al azar para el sorteo.
- **Validaciones:** 
  - No permite agregar nombres vacíos.
  - Asegura que haya al menos un nombre en la lista antes de realizar el sorteo.

## 📁 Estructura del Proyecto

```
amigo-secreto/
├── index.html      # Archivo principal del proyecto
├── style.css       # Estilos para la aplicación
├── app.js          # Lógica del proyecto en JavaScript
├── assets/         # Recursos como imágenes e íconos
└── README.md       # Documentación del proyecto
```

## 🚀 Cómo Usar

### 1. Clonar el Repositorio
```bash
git clone https://github.com/yoezequiel/Challenge-Amigo-secreto.git
cd Challenge-Amigo-secreto
```

### 2. Abrir el Proyecto
Abre el archivo `index.html` en tu navegador.

### 3. Funcionalidades Principales
1. **Agregar Amigos**:
   - Escribe un nombre en el campo de texto.
   - Haz clic en el botón **"Añadir"**.
   - El nombre se agregará a la lista visible.

2. **Visualizar Lista**:
   - La lista de amigos se actualiza dinámicamente en la página.

3. **Sortear Amigo**:
   - Haz clic en el botón **"Sortear amigo"**.
   - Se mostrará el nombre de un amigo seleccionado al azar.

## 📚 Requisitos Técnicos

- Un navegador web moderno (Chrome, Firefox, Edge, etc.).
- Para desarrollo: conocimientos básicos de HTML, CSS y JavaScript.

## 🛠️ Tecnologías Utilizadas

- **HTML5**: Estructura de la página.
- **CSS3**: Estilización de los elementos.
- **JavaScript**: Lógica para las funcionalidades interactivas.

## 📷 Captura de Pantalla

![alt text](/assets/image.png)

## 💡 Mejoras Futuras

- Agregar un botón para eliminar nombres de la lista.
- Incorporar la funcionalidad para evitar que un usuario se asigne a sí mismo.
- Agregar animaciones para mejorar la experiencia del usuario.
- Implementar una opción para reiniciar el sorteo.
