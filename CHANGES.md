# v18 · Corrección slide 15 + ajustes de texto

Base: equinoccio-cp-v17 (se conserva como respaldo; tiene el error del carrusel).

## Corrección
- 15 Un equipo que te permite crear: el carrusel se rompía en varias filas y el título se salía de la tarjeta.
  Causa: la regla de QA tipográfico de la v17 (text-wrap: balance) anulaba el "sin salto de línea" del carrusel, los marquees y las pills.
  Ahora se usa text-wrap-style: balance, que equilibra las líneas sin tocar esos elementos, y se reafirma nowrap en carrusel, marquee, pills y "Colgate-Palmolive".
  Los títulos de las dos tarjetas bajan de 64 a 56 px para caber en una línea.

## Texto
- 21: "IA sin criterio" → "AI Slop".
- 30: textos de las tarjetas resumidos:
  - 01 "Las herramientas cambian; formular bien el problema, no."
  - 02 "Tiempos, cliente e impacto en el negocio también son diseño."
  - 03 "Tu Hogar llegó al #3 resolviendo primero lo que el usuario necesitaba."

## Subir a GitHub
index.html, LEEME.txt, README.md, CHANGES.md (los assets no cambian).
