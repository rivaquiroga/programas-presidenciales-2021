# Programas elecciones presidenciales 2021

Versión en texto plano de los programas de gobierno de quienes participaron en las elecciones presidenciales de Chile.


La extracción del texto de los documentos que estaban en pdf se hizo utilizando el paquete de R :package: [{pdftools}](https://docs.ropensci.org/pdftools/) + :sparkles:expresiones regulares:sparkles:. En el caso del pdf con el programa de Sebastián Sichel, las páginas a doble columna se dividieron previamente usando [BRISS](http://briss.sourceforge.net/).

### Notas
- En todos los documentos que contenían un índice, este se eliminó.
- No se corrigió en el resultado final el uso de saltos de líneas.
- En el programa de José Antonio Kast, las notas que originalmente estaban a pie de página quedaron al final del archivo.
