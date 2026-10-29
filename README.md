# Comedor Salta · Demo Sistema RAVE (VINCULAR BUSINESS)

Demo funcional en un solo archivo (`index.html`, HTML5 + JavaScript, sin servidor ni instalación) para **Comedor Salta**, bodegón de comida casera: menú ejecutivo, menú tradicional de la casa, tablas y picadas, milanesa y pizza libres, desayunos y meriendas libres.

Diseño: blanco predominante con bordó, negro y dorado (colores de la bandera de la provincia de Salta), con **modo claro / oscuro** (botón luna/sol). Los colores están como variables CSS al inicio del bloque `COMEDOR SALTA` y se cambian en un minuto.

## Cómo abrirla
- Carta pública (cliente): `index.html`
- Carta de una mesa (QR / NFC): `index.html?mesa=I6` (I1–I12 salón, E1–E4 patio, B1–B4 barra)
- Acceso del equipo: `index.html#acceso`

## Usuarios de prueba (usuario · PIN)
| Usuario | PIN | Perfil |
|---|---|---|
| ADMIN | 1234 | Administración |
| Supervisor | 1111 | Administración |
| Caja | 0000 | Caja |
| Mozo · Ariel | 2222 | Mozo (mesas 1-6) |
| Moza · Soledad | 3333 | Mozo (mesas 7-12 y patio) |
| Barra · Pablo | 4444 | Mozo (barra) |
| Cocina · Ramón | 5555 | Cocina |
| Cocina · Ana | 6666 | Cocina |

## Qué incluye
- Circuito de comanda: Mesa/QR → Mozo → Caja → Cocina (con tiempo de entrega en vivo) → Listo → Entregado.
- **Menú ejecutivo** armable (entrada, principal, postre, bebida) con menú distinto por día, recargos y **cupos** por plato.
- **Libres** (milanesa, pizza, desayuno, merienda): se paga por persona, cuenta regresiva del tiempo libre y **rondas** sin costo que pasan por el mismo circuito.
- Asistente de voz del personal ("Pedido 12 listo", "Otra ronda mesa 6", "Mesa 5, dos milanesas napolitanas y una gaseosa").
- PedidosYa y cadetes propios, stock con fichas técnicas y trazabilidad por lote, Factura C ARCA (simulada), club de socios y cupones, personal y turnos, auditoría.
- Botón de arrepentimiento y botón de baja (Disposición 954/2025) y leyenda de datos personales (Ley 25.326) al pie de la carta.
- Circuito automático de presentación (Configuración → "Ver el circuito en automático").

## Datos: ejemplo o en blanco
En **Configuración → Datos de la demo**:
- *Restablecer con datos de ejemplo*: pedidos, mesas ocupadas, facturas y socios ficticios.
- *Dejar la demo en blanco*: queda la carta, el stock, el personal y las mesas, sin pedidos, facturas ni socios.

Los datos se guardan en el navegador (localStorage) y se sincronizan entre pestañas. Todo es ficticio (CUIT, teléfonos, proveedores, WhatsApp 5493870000000: reemplazar en Configuración).

## Publicación
Es un archivo estático: sirve en GitHub Pages (Settings → Pages → Deploy from branch → `main` / root) o abriéndolo directo en el navegador.

Desarrollado por **VINCULAR BUSINESS** · (387) 4484132 · vincularbusiness@gmail.com · "Tu idea, en buenas manos."
