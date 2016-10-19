# Practica1
Práctica para unidad 01 de LMSG01

Los documentos que se han subido en diferentes formatos son los siguientes:

1. unidad01.css
2. unidad01.html
3. unidad01.ps
4. unidad01.rtf
5. unidad01.xml

Dichos documentos se han subido al repositorio [**_GITHUB_**] (www.github.com)


### Pasos para realizar un repositorio:

1. Una vez estamos en la página web indicada anteriormente, **_GITHUB_**, hay que darse de alta mediante un nombre de usuario, un correo electrónico y una contraseña, como se puede ver a continuación:
![](https://lh3.googleusercontent.com/ggw64QkZXs_fwiGDuejegMrO6ev_oFIYqza5N2b1MDJZugMS5FEKQznyBEknuXDGu3Z08bLpK9GT-8g=w1920-h876)

2. A continuación se debe validar el correo electrónico con el enlace que se ha recibido en el correo con el que se dió de alta el usuario
![](https://lh3.googleusercontent.com/jrz95sWdvYJ3xYT-1hwPSC4uqDICCkzNJqoBUmfTZ3V4fcoXzML61cXpgN5W64fAi98oNmlN5oWNYmk=w1920-h876)

3. Y una vez realizada la validación se recibirá otro correo dando la bienvenida a **GITHUB**
![](https://lh6.googleusercontent.com/L5IW1C3M3NIcRFarzbNnryskpzC7xL4wWDjcU4oHOOVoyr7Z5c1PIooJSLqyo9Ljfa0kihOIvq4hv9k=w1920-h876)

4.  Ya se puede empezar a crear un repositorio o seguir la [guía de ayuda] (https://guides.github.com/activities/hello-world/?utm_source=onboarding-series&utm_medium=email&utm_content=hello-world-link&utm_campaign=welcome-email) que se facilita en la página web, es muy útil e intuitiva.


### Contenido documentos

>_unidad01.css_

body { font: normal 1em Verdana; margin: 1em 10%;}
h1 { font: italic 3em Georgia; color: rgb(23, 109, 109); margin: 1em 0 1em;}
img { margin: 0 20px 0 0; }
h1 img { marginbottom:
20px;
}
small { color: #666666; }


>_unidad01.html_

<!DOCTYPE html>
<html>
<head>
<title>Jen's Kitchen</title>
<link rel="stylesheet" href="kitchen.css" type="text/css" >
</head>
<body>
<h1><img src="foods.gif" alt="food illustration"> Jen&rsquo;s Kitchen</h1>
<p>If you love to read about <strong>cooking and eating</strong>, would like to find out
about
of some of the best restaurants in the world, or just want a few choice recipes to add to
your
collection, <em>this is the site for you!</em></p>
<p><img src="spoon.gif" alt="spoon illustration"> Your pal, Jen at Jen's Kitchen</p>
<hr>
<p><small>Copyright 2011, Jennifer Robbins</small></p>
</body>
</html>


>_unidad01.ps_

%!PS
/Courier % Elige el tipo de letra
20 selectfont % Establece el tamaño de la letra y
% la toma como el tipo de letra en uso
72 500 moveto % Coloca el cursor en las coordenadas
% 72, 500 (contando los píxeles desde
% la esquina izquierda de la página)
(Hola mundo! Bienvenido a LMSGI) show % Escribe el texto entre paréntesis,
showpage % Imprime el resultado


>_unidad01.rtf_

{\rtf1\ansi\ansicpg1252\deff0\deflang3082{\fonttbl{\f0\fnil\fcharset0 Calibri;}}
\viewkind4\uc1\pard\sa200\sl276\slmult1\lang10\f0\fs22 soy \i cursiva\i0\par}


>_unidad01.xml_

<?xml version="1.0" encoding="iso-8859-1"?>
<!DOCTYPE biblioteca>
<biblioteca>
<ejemplar tipo_ejem="libro" titulo="XML practico" editorial="Ediciones Eni">
<tipo> <libro isbn="978-2-7460-4958-1" edicion="1" paginas="347"></libro> </tipo>
<autor nombre="Sebastien Lecomte"></autor>
<autor nombre="Thierry Boulanger"></autor>
<autor nombre="Ángel Belinchon Calleja" funcion="traductor"></autor>
<prestado lector="Pepito Grillo">
<fecha_pres dia="13" mes="mar" año="2009"></fecha_pres>
<fecha_devol dia="21" mes="jun" año="2009"></fecha_devol>
</prestado>
</ejemplar>
<ejemplar tipo_ejem="revista" titulo="Todo Linux 101. Virtualización en GNU/Linux" editorial="Studio Press">
<tipo>
<revista>
<fecha_publicacion mes="abr" año="2009"></fecha_publicacion>
</revista>
</tipo>
<autor nombre="Varios"></autor>
<prestado lector="Pedro Picapiedra">
<fecha_pres dia="12" mes="ene" año="2010"></fecha_pres>
</prestado>
</ejemplar>
</biblioteca>
