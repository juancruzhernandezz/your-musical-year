<p align="center"><img src="logo.svg" width="110" alt=""></p>

# Your musical year

Tu historial de Spotify, contado mejor: mes por mes, día por día y hora por hora.

Todo se procesa **en tu navegador**: tus datos no se suben a ningún lado.

### [Abrir la página →](https://juancruzhernandezz.github.io/your-musical-year/)

## Qué muestra

- **Resumen anual**: minutos totales, top artistas, canciones y álbumes, racha más larga, sesión más larga, índice de impaciencia (cuánto salteás), descubrimientos, dispositivos y países.
- **Mes por mes**: el mes fuerte del año y, para cada mes, su artista y su canción.
- **Calendario**: cada día del año coloreado según cuánto escuchaste. Tocás un día y ves todo lo que sonó, en orden.
- **Hora del día**: mañana, siesta, tarde, noche, previa (viernes y sábado de 22 a 2) y madrugada, con un mapa de calor de día × hora.
- **La carrera**: el top 10 acumulado de artistas o canciones, animado a lo largo del año.
- **Obsesiones**: canciones que de golpe escuchaste mucho más que lo normal, cuándo empezaron y si las soltaste.

## Cómo usarlo

1. Pedí tus datos en [spotify.com/account/privacy](https://www.spotify.com/account/privacy/) y marcá **"Extended streaming history"**.
2. Cuando te llegue el mail (puede tardar unos días), descargá `my_spotify_data.zip`.
3. Abrí la página y soltá el zip. También acepta los archivos `Streaming_History_Audio_*.json` sueltos, o el historial corto de "Account data".

¿Todavía no tenés tus datos? Tocá **"Probar con datos de ejemplo"**.

### Sin instalar nada

Es un único archivo `index.html`. Podés:

- **Usarlo online**: [juancruzhernandezz.github.io/your-musical-year](https://juancruzhernandezz.github.io/your-musical-year/).
- **Abrirlo en tu compu**: descargá `index.html` y hacé doble clic. Funciona igual.

## Imágenes

Las tapas y fotos se buscan en vivo, desde tu navegador:

- Canciones: oEmbed de Spotify, usando el código de cada canción que trae tu historial.
- Artistas, álbumes y plan B de canciones: API pública de Deezer.

Si no hay internet o no se encuentra una imagen, queda un avatar de color. Las imágenes encontradas se guardan en tu navegador.

## Publicarlo en GitHub Pages

En el repo: **Settings → Pages → Build and deployment → Source: Deploy from a branch → Branch: `main` / `(root)` → Save**. En un par de minutos queda en `https://<tu-usuario>.github.io/<nombre-del-repo>/`.

---

Proyecto independiente, sin relación con Spotify. "Spotify" y "Wrapped" son marcas de Spotify AB.
