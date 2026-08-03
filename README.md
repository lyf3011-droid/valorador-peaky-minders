# Valoración Peaky Minders

Aplicación web formativa para aprender a analizar y valorar una empresa cotizada.

| Archivo | Qué es |
|---|---|
| **`index.html`** | La guía: los 25 datos que hay que conseguir, de dónde sale cada uno, qué significa y qué trampa tiene. Con un ejemplo completo resuelto a mano. |
| **`valorador.html`** | La aplicación: seis preguntas, diez años de datos, once gráficas y el precio al final. |

## Cómo se usa

1. Abre la **guía** y lee los 25 datos. Escribe el ticker: los enlaces a las cuentas de esa empresa se generan solos.
2. Pasa al **valorador**. El botón «Ejemplo META» lo rellena con diez años reales para que veas cómo funciona.
3. Sustituye los datos por los de tu empresa: selecciona la fila entera en la web de origen, `Ctrl+C`, y pega en la primera casilla. Los diez años se rellenan de golpe.

## Notas técnicas

- Funciona con doble clic, **sin instalar nada y sin conexión**. Los únicos botones que salen a internet son los opcionales que consultan la cotización.
- **Ningún dato que introduzcas sale de tu navegador.** No hay servidor, ni base de datos, ni analítica.
- Lo único que se guarda en tu equipo es si prefieres el sonido encendido o apagado.
- Cero dependencias externas: no carga librerías, ni tipografías, ni scripts de terceros.

## Límites del método

**No sirve para bancos, aseguradoras ni REITs.** En una entidad financiera la deuda es su
materia prima, no un riesgo, así que el Enterprise Value y el ratio deuda/EBITDA no
significan nada. En un REIT la depreciación contable hunde artificialmente el beneficio y
el ROIC sin que haya desgaste real. Esos casos necesitan otro marco.

---

⚠️ **Material formativo. No constituye asesoramiento financiero ni recomendación de compra
o venta de ningún valor.** Los resultados dependen por completo de los datos y supuestos
que introduzca cada persona.
