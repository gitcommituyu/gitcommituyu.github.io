---
layout: page
title:  "Conservation"
date:   2024-07-21 18:43:20 -0400
categories: s1
permalink: /:year/:categories/:title
---

# Conservación
![Revolución Francesa](/assets/images/s1/revolution.jpg)

## Problema a Resolver
En 1789, en el contexto de la [Revolución Francesa](https://es.wikipedia.org/wiki/Revoluci%C3%B3n_francesa), la Asamblea Nacional Constituyente Francesa plocamó la [Declaración de los Derechos del Hombre y del Ciudadano](https://es.wikipedia.org/wiki/Declaraci%C3%B3n_de_los_Derechos_del_Hombre_y_del_Ciudadano), la cual sentó las bases de derechos humanos en sociedad; sin embargo, esta declaración dejó notablemente fuera a las mujeres, pues esta declaración indicaba que los derechos solo son para ciudadanos, y los ciudadanos solo podían ser hombres. En respuesta a esto, [Olympe de Gouges](https://es.wikipedia.org/wiki/Olympe_de_Gouges), una activista y feminista francesa plocamó la [Declaración de los Derechos de la Mujer y de la Ciudadana](https://es.wikipedia.org/wiki/Declaraci%C3%B3n_de_los_Derechos_de_la_Mujer_y_de_la_Ciudadana), siendo uno de los primeros documentos históricos que proponen la equidad de género.

Tú perteneces a un equipo de conservación histórica que buscará conservar este documento de manera digital, para que así futuras generaciones puedan acceder a este. Una investigadora ya ha anotado la traducción del documento, ahora el trabajo de tu equipo será transcribirlos primeros 4 artículos de la Declaración de los Derechos de la Mujer y de la Ciudadanía a un archivo llamado `transcript.txt`.

## Distribución de Código
Para este problema, deberás descargar la distribución del código en tu entorno de Codespaces. Para ello, sigue los siguientes pasos:

+ Descarga la distribución del código
    * Accede a tu GitHub Codespaces de Git Commit:  [![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/gitcommituyu/codespace)

    * Ejecuta `cd` en tu terminal. Debiéses encontrar que tu ventana de terminal debiése asemejar la de abajo:
    ```
    $
    ```

    * Ahora ejecuta
    ```
    wget
    ```
    para descargar el archivo ZIP llamado `conservation.zip` en tu entorno de Codespaces.

    * Luego ejecuta
    ```
    unzip conservation.zip
    ```
    para descomprimir el archivo ZIP y obtener una carpeta llamada `conservation`. Ya no necesitas el archivo ZIP, por lo que puedes eliminarlo ejecutando
    ```
    rm conservation.zip
    ```

    * Ahora ejecuta
    ```
    cd conservation
    ```
    para dirigirte a la carpeta `conservation`. Debiéses encontrar que tu ventana de terminal debiése asemejar la de abajo:
    ```
    conservation/ $
    ```

    * Si todo ha salido bien, al momento de ejecutar
    ```
    ls
    ```
    debiéses encontar un archivo llamado `transcript.txt` en tu carpeta `conservation`.



## Detalles de Implementación
En grupos de 2 a 4 personas, completen la implementación de `transcript.txt` tal que sean conservados los primeros 4 artículos de la Declaración de los Derechos de la Mujer y de la Ciudadana, de tal manera que:

* Todo el código deberá ser almacenado en un repositorio de GitHub llamado `conservation-gitcommit`. (¡Este repositorio debe ser creado por uno de ustedes!)
* Cada persona debe utilizar una rama con el nombre `transcript-name` con `name` siendo el nombre de usuario de GitHub de la persona.
* Luego de que cada persona haya transcrito sus partes, deberán asegurarse que todas las transcripciones convergan en la rama `main` mediante *pull-requests*. (¡Cuidado con los merge conflicts!)
* Deben documentar por lo menos un problema que encuentren durante el proceso de la transcripcción en el apartado de Issues de GitHub.

## Cómo testear tu implementación
Para testear la correctitud de tu implementación, puedes ejectuar el siguiente comando en tu terminal:
```
check50 gitcommituyu/problems/2024/conservation
```
*Importante: Este problema no es evaluado.*

## Reconocimientos
Imagénes de la [Declaración de los Derechos de la Mujer y de la Ciudadana](https://es.wikipedia.org/wiki/Declaraci%C3%B3n_de_los_Derechos_de_la_Mujer_y_de_la_Ciudadana) obtenidas 


