Hypertext Markup Language

Anatomia de una pagina web
========

pagina index.html
    Es la pagina que el servidor va a buscar de 1ra instancia, si no, tendremos que configurar el servidor para modificar el archivo principal.

primeras lineas
    lang: En que idioma viene la pagina web
    head: Todo lo que necesita la web para poder ver la pagina, este codigo no es visible para el usuario
    body: Contiene el tema principal de la pagina

HEAD
    -meta: da cierta infomacion al navegador para que sepa como tratar nuestro proyecto, los metas se escriben por separado.
        charset: especifica los caracteres especiales
        name: ayuda a los buscadores a encontrar nuestra pagina web(CEO).
        name: robot --- con esto le daos autorizacion a los robots que ayuden a posicionar nuestra pagina en la busqueda.
        viewport: pagina responsiva, esto para la experiencia de usuario.

    -Link: enlaza los archivos css a los archivos html

BODY
    etiquetas contenedoras
        header: cunciona como el encabezado de las paginas web
        main: contenido principal
        footer: pie de pagina
        div: etiqueta comodin, puede ser cualquier etiqueta de html
        action, section, nav, ol, ul...

    etiqueta de contenido
        p, h1..h6, li

    Imagenes - tipos
        IMPORTANTE: en promedio la imagen debe pesar entre 70kb y 100kb, puedes comprimir imagenes en tinypng o verexif
        lossy : las imagenes tiene perdida de calidad y de tamaño
        lossless : No tienen perdida, son pequeñas, como logotipos o iconos

        formatos
        PNG 8 - ocupa hasta 256 colores, es tipo lossless no tiene perdida
        PNG 24 - es mas pesado, pero puedes manejar la transparencia
        JPG / JPEG - tipo lossy, pierde calidad, pesa poco y se ve mas pileleada
        SVG - tipos lossless es muy liger, sirve para iconos o logotipos, usada con pantalla de retina, nunca se pierde calidad ya que se adapta a la pantalla