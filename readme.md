
Temas a tratar 

- Definicion de RWD
- Deficinion y ejemplo de principales enfoques de RWD
- Definicion y ejemplo de media queries
- Ejemplo practico de uso de media queries tanto en enfoque Desktop First como Mobile First
- Creacion de Componente Footer aplicando RWD
- No olvidar hacer resumen en archivo readme.md
- Subir a git hub pages y pasarme enlace por interno


# Responsive Web Design

Practicas o maneras en la que hacemos que la aplicación o pagina web se vuelva adaptable a los distintos viewport que hayan.

## Enfoques:

1. Desktop First: empezamos en una resolución de escritorio, para adaptarla a la versión mobile. Max-width
2. Mobile First: empezamos en una resolución de celular, al ser más pequeño permite un diseño más rápido. Min-width

Para acoplar de una a otra versión se dificulta el trabajo. Más sencillo es de mobile a desktop, dado que se agregan cosas en vez de quitarse.

## Media Queries

Definicion:

limite de cambio para establecer distintos estilos para el mismo elemento

Ejemplo:

DESKTOP:

@media(max-width:800px){

    .box{

        background-color: blue;

    }

}

MOBILE:

@media(min-width:600px){

    .box{

        background-color: yellow;

    }

}