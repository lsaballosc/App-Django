Proyecto Splines - Django

Este proyecto es una aplicación web desarrollada con Django para el cálculo y visualización de **splines** (interpolación por tramos). Es un sistema educativo orientado al aprendizaje y práctica de métodos numéricos.

 Funcionalidades principales

- Cálculo de splines lineales, cuadráticos y cúbicos.
- Visualización gráfica de los resultados.
- Interfaz amigable con imágenes y paneles explicativos.
- Gestión de entradas por el usuario para generar las curvas interpoladas.

 Tecnologías utilizadas

- Python 3.12
- Django
- HTML5, CSS3
- JavaScript (gráficas)
- SQLite (por defecto)
Instalación

1. Clona este repositorio:
   ```bash
   git clone https://github.com/LeonelSaballos/Proyecto-Splines--Django-python-.git
   cd Proyecto-Splines--Django-python-/proyecto-splines/sistema

  2. Crea un entorno virtual
     En windows:
        bash 
     python -m venv env
.\env\Scripts\activate

     linux/Mac:
          python3 -m venv env
source env/bin/activate

3. Instala las depencias:
   pip install -r requirements.txt
4. Ejecuta migraciones
   python manage.py migrate
5. Inicia el servidor:
   python manage.py runserver

   6. abre tu navegador con la URL.

Estructura relevante
splines/: App principal que contiene la lógica del proyecto.

static/: Imágenes, hojas de estilo y recursos gráficos.

templates/: Plantillas HTML.

utils.py: Funciones para el cálculo de interpolaciones.



Autor: Leonel Saballos
