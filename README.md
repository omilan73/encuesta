# encuesta
sistema de ReviewShield
*********CLIENTE NUEVO*****
modificar archivo index encuesta (nombre.html):
6.- "Título"
14.- Logotipo.
29.- google directo
56.- archivo feedback

modificar pagina feedback (fb_nombre.html):
6.- Título.
14.- Logo.
24.- Cliente = nombre del cliente (ligado a filtro make)
47 y 58.- Política de privacidad

modificar política de privacidad (pp_nombre.html)
15.- Logotipo
30.- Nombre del responsable
31.- Marca comercial.
32.- Contacto (email)
33.- Sitio web
84.- email (para uso de derechos)
-------crear router en make----
-Línea de conexión con telegram (botón derecho)
-Add router
-Telegram bot
   -> Send a text message
-----Entre el router y el telegram bot
        Set up a filter
        Label: Nombre
       Condition: 1. CLiente
       Text operators equal to (case insesitive)
        Nombre en feedback
__________
 En el telegram bot (nuevo)
  Chat ID: 77777777? (del cliente)
Text:
Cliente: 1.cliente
Comentario: 1.Comentario
Contacto: 1.Contacto
____________________
En el telegram del cliente:

@getidsbot  (para sber el ID) 
@linkfortis_alertas_bot   (start)
