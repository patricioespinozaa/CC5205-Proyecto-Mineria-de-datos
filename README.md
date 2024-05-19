# CC5205 - Proyecto-Mineria de datos

## Grupo 1

Integrantes | Sección:
- Javiera Romero | 1  
- Patricio Espinoza | 2
- Rodrigo Díaz | 1
- Scarlett Plaza | 2
- Vicente Thiele | 2

## Dataset

URL: https://huggingface.co/datasets/maharshipandya/spotify-tracks-dataset

## Motivación
La industria musical ha estado en ascenso por décadas, últimamente la forma más popular para consumir música es a través de plataformas tales como Spotify, Apple Music, Soundcloud, etc. Siendo el más popular de estas Spotify, es interesante ver cómo el éxito de ciertos géneros/artistas ha cambiado gracias a esta forma de consumo, siendo importantes los algoritmos de recomendación a usuarios, las playlists hechas por la plataforma para destacar artistas de cierto género y el compartir tu música con los demás.

Es impresionante ver cómo las playlists mencionadas anteriormente creadas por Spotify tales como "Viva Latino" "Rock Classics" "K-Pop ON!", etc. Cuentan cada una con más de cinco millones de likes otorgados por usuarios que disfrutan de dichos específicos géneros, esta forma de categorización de la música es incluso tan importante para la plataforma que en el menú de exploración principal es el filtro recomendado para buscar tu música preferida, sugiriéndolo por sobre una búsqueda por artista o década.

Creemos que, dado esto y la gran cantidad de datos disponibles de la plataforma, es posible estudiar una conexión entre características cuantificables de las canciones y el género al que estas pertenecerán.

## Preguntas y problemas

(1) ¿Es posible predecir el género al que pertenece una canción de acuerdo a las variables musicales tales como el tempo, la valencia musical, cantidad de beats, entre otros?

Utilidad: Es de utilidad para que dadas las características musicales provenientes de la canción de una persona, esta sea capaz de identificar cómo será generalmente clasificada su canción con respecto a otras similares.

(2) ¿Existen géneros que, pese a ser distintos, sus canciones tienen atributos similares? ¿Y viceversa?

Utilidad: Gracias a esto se podrán agrupar los 114 géneros del dataset en clusters para así obtener los grupos de géneros más importantes del dataset, es decir, aquellos que aportan una característica diferente notoria a una canción.

(3) ¿Los géneros con más canciones explícitas comparten características entre ellos?

Utilidad: Permitirá saber si es un criterio de utilidad para identificar géneros con esta característica en común, y en dicho caso indagar en otros atributos musicales que permitan construir modelos, como por ejemplo los árboles de decisión.

## Resultados Hito 1:
