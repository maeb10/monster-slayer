# MONSTER SLAYER GAME

Esta aplicación es una simulación de un juego de un asesino de un monstruo.

El objetivo del juego es matar al monstruo (quitandole todos los puntos de vida) usando las distintas acciones (botones) que se muestran en pantalla sin que el jugador muera en el intento.

## Tipos de Resultados

- ***Jugador es ganador***: Cuando le quita todos los puntos de vida al monstruo sin terminarse sus puntos de vida.
- ***Monstruo es ganador***: Cuando le quita todos los puntos de vida al jugador sin terminarse sus puntos de vida.
- ***Empate***: Cuando el jugador y el monstruo se quedan sin vida al mismo tiempo.

## Funcionamiento de los botones

- ***Attack***: Inflinge daño al monstruo (entre 5 y 12 de daño) y después el monstruo contraataca al jugador causandole daño (entre 8 y 15 de daño).
- ***Special Attack***: Inflinge más daño al monstruo (entre 10 y 25 de daño) y después el monstruo contraataca al jugador causandole daño (entre 8 y 15 de daño). Se puede usar al inicio del juego y después cada 3 rondas.
- ***Heal***: Sana al jugador (entre 8 y 20 de vida) y después el monstruo lo ataca mientras está sanando causandole daño (entre 8 y 15 de daño).
- ***Surrender***: El jugador se rinde y por lo tanto pierde el juego.

***Nota***: Al presionar cualquiera de los siguientes botones de acción (***Attack***, ***Special Attack*** y ***Heal***) contará como una ronda.

Las tecnologías que se utilizaron en este proyecto son:

- HTML
- CSS
- JavaScript
- Vue

Para poder ver la aplicación visita el siguiente [link](https://maeb10.github.io/monster-slayer/).
