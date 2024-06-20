### Cómo ejecutar el proyecto:

Clona el repositorio y ábrelo en la interfaz de la línea de comandos: 

```
git clone https://github.com/tripleten-com/kittygram_plus_es.git
```

```
cd kittygram_plus
```

Crea y activa un entorno virtual:

```
python3 -m venv env
```

* Para Linux/MacOS

    ```
    source env/bin/activate
    ```

* Para Windows

    ```
    source env/scripts/activate
    ```

Instala las dependencias del archivo requirements.txt

```
python3 -m pip install --upgrade pip
```

```
pip install -r requirements.txt
```

Ejecuta las migraciones:

```
python3 manage.py migrate
```

Ejecuta el proyecto:

```
python3 manage.py runserver
```
