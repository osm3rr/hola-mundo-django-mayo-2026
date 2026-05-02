# Hola Mundo en Django

Proyecto de ejemplo en Django que muestra una página simple con el mensaje "Hola Mundo en Django". Ideal para aprender la estructura básica de un proyecto Django, cómo configurar el entorno y ejecutar la aplicación localmente.

---

## 🚀 ¿Qué incluye este proyecto?

- Proyecto Django principal: `base_project`
- Aplicación Django: `pages`
- Plantillas HTML simples: `templates/index.html`
- Base de datos SQLite predeterminada: `db.sqlite3`
- Archivo de configuración principal de Django: `base_project/settings.py`

---

## 🧱 Estructura del proyecto

```text
hola_mundo_django/
├── db.sqlite3
├── manage.py
├── requirements.txt
├── base_project/
│   ├── __init__.py
│   ├── asgi.py
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
├── pages/
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── tests.py
│   ├── urls.py
│   └── views.py
├── templates/
│   └── index.html
└── README.md
```

---

## 🛠️ Requisitos

- Python 3.8 o superior
- Django 4.x (o la versión indicada en `requirements.txt`)
- Virtualenv o entorno virtual recomendado

---

## ⚡ Instalación y ejecución

1. Abre una terminal en la carpeta del proyecto:

```bash
cd c:\Users\Ada-Amarillo\Documents\ebook\hola_mundo_django
```

2. Crea y activa un entorno virtual (recomendado):

```bash
python -m venv .venv
.\.venv\Scripts\activate
```

3. Instala las dependencias:

```bash
pip install -r requirements.txt
```

4. Aplica migraciones:

```bash
python manage.py migrate
```

5. Ejecuta el servidor de desarrollo:

```bash
python manage.py runserver
```

6. Abre el navegador y visita:

```text
http://127.0.0.1:8000/
```

---

## 🌐 ¿Qué verás?

La página principal muestra un encabezado con el texto:

- `Hola Mundo en Django`

Este proyecto es un buen punto de partida para:

- Aprender a trabajar con vistas Django
- Configurar rutas en `urls.py`
- Usar plantillas HTML básicas
- Entender la arquitectura de un proyecto Django

---

## 📁 Archivos clave

- `manage.py`: Script de administración de Django.
- `base_project/settings.py`: Configuración principal del proyecto.
- `base_project/urls.py`: Enrutamiento global del proyecto.
- `pages/views.py`: Vista que renderiza la página de inicio.
- `pages/urls.py`: URLs locales de la app `pages`.
- `templates/index.html`: Plantilla HTML principal.

---

## 🧪 Siguientes pasos sugeridos

- Añadir más páginas y rutas
- Crear un modelo en `pages/models.py` y registrar en `admin.py`
- Usar `templates` para renderizar contenido dinámico
- Configurar estilos CSS o Bootstrap

---

## 📌 Notas

- El proyecto usa SQLite para facilitar la configuración inicial.
- Si necesitas actualizar Django o dependencias, modifica `requirements.txt` y reinstala.

---

## 💬 Soporte

Si deseas mejorar este proyecto, puedes:

- agregar nuevos templates
- añadir una app adicional
- configurar autenticación de usuarios
- implementar formularios con Django Forms

¡Disfruta aprendiendo Django! 🎉
