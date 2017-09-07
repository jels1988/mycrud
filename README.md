## My Crud

### Instalación y Ejecución

- Crear el usuario mycrud en Postgresql y la base de datos mycrud asignandole el usuario mycrud como owner.

- De preferencia crear un entorno virtual para correr el proyecto:

    `python3 -m venv nombre_entorno`

- Activar el entorno virtual:

    `source nombre_entorno/bin/activate`

- Ingresar a la carpeta donde se ha clonado el proyecto.

    `cd mycrud`

- Instalar los paquetes de requirements.txt

    `pip install -r requirements.txt`

- Hacer las migraciones:

    `python manage.py migrate`

- Correr el proyecto:

    `python manage.py runserver`