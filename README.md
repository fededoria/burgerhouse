Página web simple tipo landing page con menú de navegación arriba, contenido, y footer abajo

Descripción compañia ficticia:
Empresa dedicada a organizar actividades al aire libre para aventureros.

Nombre: Burguer House

---

# Assets
Elementos para usar en la página

## Fonts
- Alfa Slab One regular 400 → Títulos
- Bebas Neue regular 400 → Títulos de tarjetas
- Lato regular 400 → texto general

## Imagenes necesarias
- logo small : hamburguesa monoline con nombre al costado
- hero.png : hamburguesa junto a un vaso de gaseosa, sin background
- grilla x 3: foto de plato con hamburguesas
   grid-big   grid-small1   grid-small2
- card x 3: hamburguesa sin background
   enjoy1   enjoy2   enjoy3
- slider: foto hamburguesa de perfil nombre "events"
- form contacto: 3 imagenes sin background: pan con semillas de sesamo, botella salsa picante, ingredientes
- footer.jpg: foto ancho completo para usar de fondo

## Franjas
1. Header
2. Main con 6 secciones
    - hero
    - grilla platos
    - card x3, hamburguesas
    - slider, quienes somos
    - contacto
3. Footer

## Colores

#0B483C Verde oscuro (secundario)
#A5E101 Verde claro (acento)
#1B1B1B Negro (primario)
#333333 Gris oscuro (complementario)
#F4F4F4 Beige claro (bg)

---

# Estructura

Es una landing page con secciones a pantalla completa

## Header
- logo a izquierda
- menu centro (los enlaces son las 6 secciones del main menos el hero, o sea 5)
- botón CTA → Contacto

## 1 - Hero
- Imagen sin fondo
- Encabezado h1 con el título
- frase
- Botón CTA

Hero Section:

Título: Burguer week en líneas suparadas, palabra 'burguer' más grande
Frase gancho: "Despierta tu espíritu aventurero con Reyes Outdoor. ¡Explora la naturaleza y vive experiencias inolvidables!"

## 2 - Grilla platos x 3
grid: 2 columnas 3 filas

columna izquierda ocupa dos filas
  plato 1:
  - h3
  - p con Most popular burguer

columna derecha dividida en dos filas
  plato 2
  - h3
  - more fun more taste
  plato 3
  - h3
  - fresh & chilli

## 3 - Cards hamburguesas especiales
- h2 Choose & enjoy
- texto p 'lorem'.

- contenedor sin formato conteniendo:
    - 3 tarjetas

    Cada tarjeta es un 'div'con clase "card" (ver si pongo card-1, card-2, card-3) tiene:
    - foto hamburguesa sin background
    - heading h3 nombre servicio
    - 'p'
    - botón rojo rectangular, hecho sin etiqueta buttom


## 4 - Slider quienes somos
- imagen de fondo
- div.wraper → display flex o grid con 2 elementos en column
    div columna izquierda:
    - discover
    - heading h4 'Upcoming events'
    - p 
   div columna derecha: foto
aplicar sombra al wrapper


## 5 - Formulario contacto
Reservation
Book your table
Formulario de contacto
- nombre | apellido (dos imputs separados uno al lado del otro)
- email
- "Cómo llegaste a nosotros"
    radio button= publicidad, recomendación, redes sociales, buscando en internet, otro
- boton enviar

Frase:

¡Cuéntanos tu aventura! Completa el siguiente formulario y te contactaremos para asesorarte y ayudarte a planificar tu próxima aventura.

## Footer
Doble sección:
- fondo bg-accent con "Reyes Outdoor: Aventuras - Naturaleza - Experiencias inolvidables"
- fondo bg-main con copyright &copy 2024 | Hecho por mi [emoji rayo] | Gracias por visitarnos
