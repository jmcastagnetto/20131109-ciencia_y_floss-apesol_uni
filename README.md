# Ciencia y Código Libre

Charla acerca de la relación entre la Ciencia y el Código Libre en el evento "Software Libre en el Perú", organizado por APESOL en la UNI.

El archivo principal es index.Rmd (R-Markdown), el cual es compilado a Markdown y HTML usando knitr y Slidify.

He hecho modificaciones simples a los estilos (ver los archivos *-patch) que vienen con la versión estable sde Slidify

Requisitos:

- [R](http://www.r-project.org/)
- [Slidify](http://slidify.org/) ([slidify en github](https://github.com/ramnathv/slidify))

Para compilar, ejecutar en R:

~~~ R
require(slidify)
slidify(index.Rmd)
~~~

-- Jesús M. Castagnetto
