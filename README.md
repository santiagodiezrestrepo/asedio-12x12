# Asedio 12×12

Variante de ajedrez de asedio en un tablero de 12×12 con cuatro fichas nuevas: **catapulta**, **ariete**, **arquero** y **piquero**. Se juega en el navegador, contra la CPU o a dos jugadores, con un manual de movimientos al lado del tablero.

Todo el juego está en un único archivo: [`index.html`](index.html). Basta con abrirlo en el navegador; no necesita instalación ni servidor.

## Fichas nuevas

| Ficha | Movimiento | Captura | Especial |
|---|---|---|---|
| Catapulta | 1 casilla en horizontal o vertical | Dispara a una ficha a exactamente 3 o 4 casillas en línea recta, por encima de todo, sin moverse | Recarga un turno tras disparar |
| Ariete | Hasta 3 casillas hacia delante o hacia los lados; 1 hacia atrás | Arrolla todas las fichas enemigas que atraviesa | Inmune a los arqueros |
| Arquero | 1 casilla en cualquier dirección | Dispara en diagonal a 1–3 casillas con la línea despejada, sin moverse | No daña al ariete |
| Piquero | 1 casilla en horizontal o vertical | Hacia delante a 1 o 2 casillas, o 1 en diagonal hacia delante | Los caballos no pueden capturarlo |

## Reglas principales

- Gana quien da jaque mate. Los disparos y las embestidas también dan jaque.
- El peón avanza 1 o 2 casillas en su primer movimiento y corona como cualquier ficha salvo el rey.
- Sin enroque ni captura al paso.
- Tablas por rey ahogado, por 50 jugadas por bando sin capturas ni movimientos de peón, o si solo quedan los reyes.

## Equilibrio

Los valores de las fichas (dama 10, torre 5, alfil y caballo 3, ariete 3,5, catapulta 3, arquero 2, piquero 1,5, peón 1) se calibraron con partidas simuladas CPU contra CPU. En 300 partidas en 12×12, blancas y negras ganaron casi lo mismo (132 frente a 131).
