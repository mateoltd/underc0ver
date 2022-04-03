# Underc0ver

Canal oficial del ZeroDay UnderC0ver. Unicamente funcional en Chrome OS.

# ¿Cómo funciona?

La mayoría de aplicaciones para monitoreo de pantalla que existen en Chrome OS a día de hoy son extensiones, esto quiere decir que estas herramientas poseen determinados permisos.
En este caso, nos hemos dado cuenta de que dichas extensiones no poseen/requieren acceso a ningún otro protocolo distinto de HTTP y HTTPS.
Por tanto, mediante HTML, usando el método iFrame, se ha creado un navegador interno que funciona a través del protocolo FILE. 
Para remover los bloqueos de red se usa un proxy al que se accede por este mismo procedimiento.
