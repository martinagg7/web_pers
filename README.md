
# Web Personal

Este es un proyecto de **Web Personal** desarrollado en Django para asignatura DOO. El objetivo principal es ofrecer un portafolio donde se pueden gestionar y mostrar proyectos de manera organizada. 

## Estructura del Proyecto

```plaintext
.
├── manage.py                  # Archivo principal para ejecutar comandos de Django
├── requirements.txt           # Dependencias necesarias para ejecutar el proyecto
├── vercel.json                # Configuración para intentar desplegar en Vercel
├── db.sqlite3          
├── .gitignore     
├── webpersonal/          
│   ├── core/                  # Aplicación principal
│   │   ├── migrations/        
│   │   ├── templates/         
│   │   ├── __init__.py        
│   │   ├── admin.py           
│   │   ├── apps.py            
│   │   ├── models.py         
│   │   ├── tests.py           
│   │   ├── views.py
├── media/                     # Carpeta para almacenar archivos subidos
├── portfolio/                 # Aplicación secundaria para gestionar proyectos del portafolio
├── staticfiles/               # Archivos estáticos recolectados
├── README.md
```
## Cómo Ejecutar el Proyecto

Sigue estos pasos para ejecutar la aplicación en tu entorno local:

```bash
# Clona el repositorio desde GitHub y accede a la carpeta del proyecto
git clone https://github.com/martinagg7/web_pers.git
cd web_pers

# Crea un entorno virtual para aislar las dependencias del proyecto y actívalo
python -m venv env-django
source env-django/bin/activate  

# Instala las dependencias necesarias desde el archivo requirements.txt
pip install -r requirements.txt

# Ejecuta el servidor de desarrollo local
python manage.py runserver
   pip install -r requirements.txt
   python manage.py migrate
   python manage.py runserver

```
## Desplegar Proyecto

- **Para acceder a la página principal**, abre [http://127.0.0.1:8000/](http://127.0.0.1:8000/) en tu navegador.  
- **Para acceder al panel de administración**, utiliza [http://127.0.0.1:8000/admin](http://127.0.0.1:8000/admin).  

Si aún no tienes un superusuario, créalo con el siguiente comando:  
```bash
python manage.py createsuperuser
```
### Desplegar vercel

A la derecha del repo

## Repositorio
**Nombre de usuario:** martinagg7  
**Repositorio:** [web_pers](https://github.com/martinagg7/web_pers.git)

