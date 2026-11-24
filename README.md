# Ajedrez Aventura

Aplicación web instalable (PWA) para que un niño aprenda ajedrez paso a paso, guiado por Robi, un robot entrenador.

## Qué incluye

- **Mapa de 11 misiones** que se desbloquean en orden, con gemas y rangos.
- **El mapa del tablero:** nombres de las casillas (letras y números).
- **Una misión por pieza** (torre, alfil, reina, rey, caballo, peón): recoger estrellas con la menor cantidad de movidas.
- **¿Cuánto vale?:** sumas y restas con el valor de las piezas.
- **¡Jaque! y Jaque mate:** retos de una jugada, con pista.
- **Duelo con Robi (guiado):** panel «Tu turno» con peligros, oportunidades y objetivos de apertura; casillas verdes/rojas al elegir pieza; aviso antes de un error grave; calificación de cada jugada; Robi explica sus movimientos; tres niveles de ayuda (máxima, media, ninguna).
- **Duelo con Robi:** partida completa contra la computadora en tres niveles. 5 pistas por partida (jugada sugerida, por qué, plan de 3 jugadas y estrategia), deshacer, avisos de piezas en peligro y explicación de cada jaque mate.

## Cómo instalarla

1. Abrir la página publicada en GitHub Pages con Chrome o Edge (en PC) o con Chrome (Android).
2. Tocar el botón **Instalar** de la barra superior, o el ícono de instalar de la barra de direcciones.
3. En iPhone/iPad: Safari → Compartir → *Agregar a pantalla de inicio*.

Después de la primera visita funciona sin internet.

## Notas

- El progreso se guarda en el navegador de cada dispositivo (`localStorage`); no se sincroniza entre equipos.
- El motor de ajedrez está escrito en JavaScript puro y cumple las pruebas *perft* estándar (posición inicial, Kiwipete y posición 3). El peón siempre corona en dama; no se detectan tablas por repetición ni por la regla de 50 jugadas.
- Sin dependencias ni proceso de compilación: todo está en `index.html`.
