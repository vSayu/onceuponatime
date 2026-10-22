# Personaliza la página

Abre `index.html` en el editor para cambiar los datos de la página. Las carpetas y archivos de imágenes se ponen junto a `index.html`, dentro de `img`.

## Fotos de la página

Guarda tus fotos dentro de `img/` con estos nombres exactos. Conserva la extensión `.jpg` (si tus fotos son PNG o tienen otra extensión, cambia también el nombre en `index.html`). No necesitas llenar todos los espacios: mientras falte una foto, seguirá apareciendo el recuadro con su número.

| Nombre del archivo | Espacio |
| --- | --- |
| `1.jpg` | Álbum, imagen 1 |
| `2.jpg` | Álbum, imagen 2 |
| `3.jpg` | Álbum, imagen 3 |
| `4.jpg` | Álbum, imagen 4 |
| `5.jpg` | Collage, imagen 5 |
| `6.jpg` | Collage, imagen 6 (centro) |
| `7.jpg` | Collage, imagen 7 |
| `10.jpg` | Álbum, imagen 10 |
| `11.jpg` | Álbum, imagen 11 |
| `12.jpg` | Álbum, imagen 12 |
| `carta1.jpg` a `carta5.jpg` | Fotos de la carta; una por cada número |

Los números 8 y 9 no tienen espacio en el diseño actual.

## Gatitos que caen

Pon los PNG en `img/gatos/` con estos nombres: `michi1.png`, `michi2.png` y `michi3.png`. Puedes usar uno, dos o los tres. Si un archivo no está, en su lugar aparece un gatito emoji. Para agregar más, añade su ruta a la lista `gatos` de `CONFIG` al final de `index.html`.

## Imágenes decorativas opcionales

Pon `deco1.png`, `deco2.png`, `deco3.png`, `deco4.png` y `deco5.png` dentro de `img/deco/`. Si faltan, simplemente no se muestran.

## Música de fondo

Guarda el audio como `musica.mp3` en la misma carpeta que `index.html` (no dentro de `img`). Tras ingresar la contraseña, el archivo completo empieza desde 0:00 después de 5 segundos. El volumen sube gradualmente durante 14 segundos para que la canción entre suavemente. Al llegar a 5:12.000, la pista vuelve a 0:14.625 para crear un bucle más disimulado. Si apagas y vuelves a encender el botón, vuelve a empezar desde 0:00 con el mismo fundido. Puedes cambiar estos tiempos y `volumenMusica` en `CONFIG`, al final de `index.html`. Algunos navegadores requieren que la persona toque el botón para permitir la reproducción; si lo toca antes, empieza de inmediato.

La canción que aparece más abajo en YouTube es independiente. Cambia `youtubeId` en `CONFIG` por el código que aparece después de `v=` en la dirección de YouTube. Al reproducir YouTube, se pausa la música de fondo para que no suenen las dos canciones juntas.
