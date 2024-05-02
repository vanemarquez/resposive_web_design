
# Responsive Web Design

Es una metodología, un conjunto de prácticas en las que nuestra aplicación sea adaptable, que sea vea bien, en cualquier dispositivo.


## Enfoques

Existen dos enfoques básicos a la hora de pasar un diseño a codigo los cuales son “mobile-first” y “desktop-first”.

- Mobile First: Se centra en diseñar y desarrollar sitios web comenzando por las necesidades y características principales para dispositivos móviles.

![Mobile First](https://media.licdn.com/dms/image/C5112AQG2OFr2pHFfjQ/article-inline_image-shrink_400_744/0/1520095961368?e=1720051200&v=beta&t=0duaE7JjmfrAogF4gDEdM4Acwpak7lhWzsq7nd0W-JA)


```bash
.mobile{
    background-color: black;
    width: 200px; height: 200px;
}

@media (min-width: 768px){
    .mobile{background-color: purple;}

@media (min-width: 1200px){
    .mobile{background-color: pink;}

```

- Desktop First: Implica diseñar el sitio web primero para pantallas grandes, priorizando la experiencia en computadoras de escritorio

![Desktop First](https://media.licdn.com/dms/image/C5112AQHFq6GNEs6EDA/article-inline_image-shrink_400_744/0/1520239092831?e=1720051200&v=beta&t=-6b4FF-vV-XQNoOUgnz4Wp9R3JgNCkNqSpngSXp4i2E)

```bash
.desk{
    background-color: orange;
    width: 200px; height: 200px;
}

@media (max-width: 768px){
    .mobile{background-color: purple;}

@media (max-width: 500px){
    .mobile{background-color: pink;}

```


## Media Quaries

Permiten la adaptación de diseños web a diferentes dispositivos y pantallas mediante el diseño responsive.

## Break Point

Es el ancho de un dispositivo en el cual queremos que la forma en la que mostramos nuestro contenido con CSS cambie.







