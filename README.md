# Hola! 👋

> Si es la primera vez que visitas este repo (o no lo es) y esta guía te está ayudando de alguna manera, no olvides darle una estrellita ⭐ para consultarla en futuras ocasiones

🚧 Actualmente la guía está en construcción, y se irá ampliando conforme vaya teniendo más tiempo.
Durante el proceso iré adjuntando diferentes links que son de gran utilidad y que otros compañeros del mundo del teclado han ido subiendo.

🚨 **Quiero dejar claro que no soy para nada un experto en esto, no me hago responsable de absolutamente nada. Simplemente dejo esta guía por internet para ayudar a aquellos que están empezando en este mundo.**

# Antes de empezar

## Recursos

> ℹ️ En esta sección iré dejando los links, archivos, .hex, etc. que sean interesantes. Esta sección la dejaré la primera para que no se pierdan dentro de la guía.

- [Guía oficial de Josefadamcik](https://josefadamcik.github.io/SofleKeyboard/build_guide_rgb.html)
- [Guía oficial traducida al español](https://zonekeyboards.cl/assembly-sofle-rgb)
- [Guía paso a paso con fotos](https://docs.beekeeb.com/build-guide/sofle-rgb-v2.1-soflekeyboard-build-log-guide-with-photos)
- [Documentación de QMK](https://docs.qmk.fm/#/)
- [Configurador de QMK (con el layout del Sofle)](https://config.qmk.fm/#/sofle/rev1/LAYOUT)
- [Gerbers de la PCB](https://github.com/josefadamcik/SofleKeyboard/tree/master/Gerbers/RGB)
- [Guía visual de soldadura]()

🚧 ...

## Consejos

Los consejos que voy a dejar son muy obvios, pero no está de más recordarlos. Estos consejos son los que yo he seguido y que me han ayudado a no equivocarme en el montaje del teclado.

- **Marcalo todo**: Es muy recomendable marcar cada mitad del teclado (parte superior izquierda, superior derecha, etc.). Esto te ayudará a no equivocarte a la hora de montar el teclado.

- **No te apresures**: No te apresures a montar el teclado. Toma tu tiempo y no te precipites. Equivocarte en una soldadura puede ser un problema irreversible.

- **Verifica todo**: Antes de comenzar a soldar algo, verifica que todo esté bien. Si no estás seguro, no lo hagas.

- **Investiga**: Antes de comenzar a hacer algo, no dudes en investigar. De nuevo, si no estás seguro de algo, no lo hagas.

# Componentes

> ℹ️ Esta sección contendrá la lista de todos los componentes que he utilizado para el montaje del teclado, así como el precio de cada componente de forma aproximada.

Los componentes que he utilizado son los siguientes:

| # | Obligatorio | Componente | Precio | Link | Comentarios |
| --- | --- | --- | --- | --- | --- |
| 1 | Si | *2x* [PCB](./docs/components/PCB.md) | 4'32€ | - | Pedido a JLCPCB |
| 2 | Si | *2x* Plate superior | - | - | Pedido a JLCPCB junto con la PCB |
| 3 | Si | *2x* Plate inferior | - | - | Pedido a JLCPCB junto con la PCB |
| 4 | Si | *58x* [Switch](./docs/components/Switch.md) | 24'51€ | [Link](https://es.aliexpress.com/item/1005003746169161.html) | Pedido en AliExpress. El precio es de dos cajas de 45 unidades cada una. Los mios son unos [Akko CS Lavanda](https://en.akkogear.com/product/akko-cs-lavender-purple-switch-45pcs/). |
| 5 | Si | *58x* [Keycap](./docs/components/Keycap.md) | 20'05€ | [Link](https://es.aliexpress.com/item/1005004192847697.html) | Pedido en AliExpress. El precio es de un pack completo de teclas en Inglés. |
| 6 | Si | *58x* Kailh Hotswap Socket | 8'44€ | [Link](https://es.aliexpress.com/item/1005002637150446.html) | Pedido en AliExpress en un gran lote. |
| 7 | Si | *2x* [Pro Micro (con pin header)](./docs/components/Promicro.md) | 11'03€ | [Link](https://es.aliexpress.com/item/1005001622051348.html) | Pedido en AliExpress. |
| 8 | No | *4x* Socket Header (12 pines) | 0'45€ | [Link](https://es.aliexpress.com/item/1005001610366695.html) | Es opcional, pero es muy recomendable. |
| 9 | Si | *1x* Cable USB C | 4€ | [Link](https://es.aliexpress.com/item/1005003776565766.html) | No es necesario adquirir un cable USB C super especial. Cualquier cable USB C que tengas por casa te servirá. |
| 10 | Si | *2x* Conector TRRS | 0'54€ | [Link](https://es.aliexpress.com/item/33029465106.html) | Precio de la conjunta |
| 11 | Si | *1x* Cable TRRS | 1'43€ | [Link](https://es.aliexpress.com/item/4000104350398.html) | Precio de la conjunta |
| 12 | Si | *58x* Diodos 1N4148W | 0'92€ | [Link](https://es.aliexpress.com/item/1005004617332808.html) | Precio de la conjunta |
| 13 | Si | *2x* Botón reset | 0'33€ | [Link](https://es.aliexpress.com/item/32976590241.html) | Precio de la conjunta |
| 14 | Si | *28x* Tornillo M2 (3mm) | 0'66€ | [Link](https://es.aliexpress.com/item/32810852732.html) | Precio de la conjunta |
| 15 | Si | *14x* Separador M2 (7mm) | 0'95€ | [Link](https://es.aliexpress.com/item/1005004286356432.html) | Pedido en AliExpress. Venían 50 unidades |
| 16 | Si | *10x* Pata de goma | 1€ | - | Pedido en tienda local |
| 17 | No | *2x* Pantalla OLED (128x32) (con pin header) | 5'31€ | [Link](https://es.aliexpress.com/item/32879702750.html) | Pedido en AliExpress |
| 18 |  | *2x* Socket Header (4 pines) | 1€ | - | Pedido en tienda local. Se compró uno largo y se cortó a medida. |
| 19 | No | *2x* Potenciometro EC11 (con knob) | 4'50€ | [Link](https://es.aliexpress.com/item/10000056483250.html) | Pedido en AliExpress (un pedido para los encoders y otro para los knobs). Venían 5 unidades en cada pedido. |
| 20 | No | *72x* LED SK6812 | 4'44€ | [Link](https://es.aliexpress.com/item/32782295214.html) | Pedido en conjunta |
| 21 | No | *1x* Funda | 14€ | [Link](https://es.aliexpress.com/item/1005003426184729.html) | Pedido en AliExpress |
| Total |  | - | **107'88€**| - | - |

🚧 ...

# Montaje

> ℹ️ Esta sección contendrá los pasos que he seguido para el montaje del teclado. Los pasos que vienen son los recomendados por varios compañeros, que bajo su experiencia, ha significado un montaje más sencillo.

Hay dos formas de montar el teclado:

- **La segura**: Consiste en soldar primero los componentes imprescindibles (switches, diodos, Pro Micro, etc) y luego soldar los componentes opcionales (pantalla OLED, encoders, LEDs, etc). De esta forma puedes comprobar en todo momento que todo funciona correctamente. Es más dificil de soldar por que el promicro estorba desde el principio, pero es la forma más segura de montar el teclado.

    1. Soldamos los componentes imprescindibles (`diodos, socket header, promicro`) y comprobamos que todo funciona correctamente.

    2. Soldamos los componentes opcionales (`pantalla OLED, encoders, LEDs, etc`). En este paso es muy importante comprobar que todo funciona correctamente cada vez que soldamos un componente nuevo (sobre todo en el caso de los LEDs, que recomiendo ir comprobando cada vez que soldamos un LED nuevo)

- **La cómoda**: Consiste en soldar los componentes de forma que la soldadura sea lo más sencilla posible. De esta forma, puedes soldar los componentes opcionales sin tener que soldar el promicro. Es menos dificil de soldar, pero puede dar verdaderos dolores de cabeza en caso de error.

    - El orden de soldadura sería: `diodos, LEDs, socket headers, reset, TRRS, promicro, OLED, encoders`

En mi caso, he seguido la segunda forma, ya que era la primera vez que soldaba y quería que el proceso fuera lo más sencillo posible.

## 1.- Diodos

<!-- Foto del pad -->

<!--
- Aplicar soldadura en uno de los pines del diodo
- Soldar el diodo únicamente con el pin que hemos soldado
- Aplicar soldadura en el otro pin del diodo
-->

🚧 ...

## 2.- LEDs

<!-- Fotos de los pads -->

Hay 3 tipos de montaje para los LEDs:

- **LEDs solda 

<!--
- Aplicar soldadura en uno de los pines del LED
- Soldar el LED únicamente con el pin que hemos soldado
- Aplicar soldadura en los demás pines del LED
-->

## 3.- Kailh Hotswap

<!-- Foto del pad -->

## 4.- Reset

<!-- Foto del pad -->

## 5.- TRRS

<!-- Foto del pad -->

## 6.- Socket Header (promicro)

<!-- Foto del pad -->

## 7.- Promicro

<!-- Foto del pad -->

## 8.- Socket Header (OLED)

<!-- Foto del pad -->

## 9.- OLED

<!-- Foto del pad -->

## 10.- Encoders

<!-- Foto del pad -->

## 11.- Plate superior (+ separadores y tornillos)

<!-- Foto del pad -->

## 12.- Switches

<!-- Foto del pad -->

## 13.- Plate inferior (+ tornillos)

<!-- Foto del pad -->

## 14.- Pata de goma

## 15.- Funda


<!--
Explicar las dos formas de montarlo:
- La segura: Más dificil de soldar pero mejor resolución de errores
- La tryhard: Menos dificil de soldar pero puede dar verdaderos dolores de cabeza en caso de error
-->

🚧 ...

# Programación (QMK)

> ℹ️ Esta sección explicará de forma muy sencilla como hacer tu propio firmware y ejecutarlo en tu teclado.

## Sin programación

🚧 ...

## Con programación

🚧 ...

<!--
- Como hacer tus propios dibujos en la pantalla OLED
- Como subir una imagen personalizada a la pantalla OLED
-->

# Resolución de problemas

> ℹ️ Esta sección contendrá aquellos fallos más comunes, así como una pequeña lista de pasos que debes de seguir para acotar el problema en cuestión.

🚧 ...
