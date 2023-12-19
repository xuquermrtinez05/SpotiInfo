
![SpotifyImagen](./spotify-neon-green-sw8td453uh40k0j7.jpg)
# Proyecto Spotify-API

Este proyecto utiliza la API de Spotify para realizar diversas operaciones, como buscar canciones, obtener información de artistas y crear listas de reproducción. Es una aplicación de ejemplo para mostrar cómo interactuar con la API de Spotify utilizando [Spotipy](https://github.com/plamere/spotipy), una biblioteca Python para la API de Spotify.

## Configuración

Antes de comenzar, es necesario configurar algunas cosas. Siga los pasos a continuación:

1. **Crear una aplicación en Spotify Developer Dashboard:**
   - Ve a [Spotify Developer Dashboard](https://developer.spotify.com/dashboard/applications).
   - Inicia sesión con tu cuenta de Spotify (o crea una cuenta nueva si no tienes una).
   - Crea una nueva aplicación y obtén las claves de cliente y secreto del cliente.

2. **Configurar las variables de entorno:**
   - Crea un archivo `.env` en el directorio raíz del proyecto.
   - Agrega las siguientes líneas al archivo `.env` y reemplaza `TU_CLAVE_DE_CLIENTE` y `TU_SECRETO_DE_CLIENTE` con las claves obtenidas en el paso anterior.
     ```env
     SPOTIPY_CLIENT_ID=TU_CLAVE_DE_CLIENTE
     SPOTIPY_CLIENT_SECRET=TU_SECRETO_DE_CLIENTE
     ```

## Instalación

1. **Clonar el repositorio:**
    Clona el repositorio de la api de spotify
   ```bash
   git clone https://github.com/tuusuario/spotify-api-project.git
   cd spotify-api-project

2. **Instalar dependencias:**
    Instala las dependencias necesarias
    ```bash
    Copy code
    pip install -r requirements.txt

3. **Uso:**   
Ejecuta el script principal para comenzar a interactuar con la API de Spotify:

     
    ```bash
    copy code
    python main.py
    asegúrate de tener Python 3 instalado en tu máquina.
    python main.py

## Funcionalidades
- Buscar Canciones: Realiza búsquedas de canciones por nombre.
- Información de Artista: Obtiene información detallada de un artista específico.
- Crear Lista de Reproducción: Crea una lista de reproducción personalizada.
- Contribuciones

## WIKI
Accede a la wiki desde este enlace [WIKI](https://github.com/xuquermrtinez05/SpotiInfo/wiki)


