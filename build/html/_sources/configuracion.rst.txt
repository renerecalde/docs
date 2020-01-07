Configuración
=============


.. figure:: images/06-configuracion-menu.png
   :align: right

   Menú de configuración.

El menú de configuracíon consta de las siguientes opciones:

* Canales_
* Países_
* Zonas_
* Monedas_
* `Tasas de cambio`_
* Idiomas_
* `Modos de pago`_
* `Métodos de envío`_
* `Categorías de envío`_
* `Categorías de impuestos`_
* `Tasas de impuestos`_
* Administradores_

La mayoría de las mismas se entregan configuradas por el desarrollador. Tales como: Canales, Países, Zonas, Monedas, Idiomas, Administradores.

Algunas otras deben ser configuradas por usted, dependiendo de su actividad, como por ejemplo el método de pago que acepta (contra reembolso, tarjetas, etc.) o sus estratégias de logística (delivery, encomiendas, etc.).



.. warning:: Se recomienda no modificar las configuraciones previamente establecidas. Ante cualquier duda consulte la `ayuda <contacto.html>`_ 


-----------

.. _Canales:

Canales
*******

Los canales son una forma de configurar múltiples opciones de su tienda, tales como el lenguaje y la moneda.

.. danger:: Este ítem ya se encuentra configurado por el desarrollador. Se recomienda no modificar esta sección ya que podría dañar el sistema.

.. figure:: images/07-configuracion-canales.png
   :align: center

   Canales.

.. _Países:

Países
******

El país **Argentina** se entrega configurado por defecto.

Usted puede administrar (agregar o quitar) **provincias** o incluso otros **países** donde pueda distribuír sus productos, en casos que cuente con servicios de envíos internacionales.

Para ello debe ingresar a **Editar** en el caso que quiera modificar las provincias de Argentina.

O debe hacer click en **Crear** en caso de desear agregar otro País.

.. figure:: images/08-configuracion-paises.png
   :align: center

   Configuración de países y provincias.



.. _Zonas:

Zonas
*****

En esta sección se pueden agrupar diferente **regiones de venta y distribución** que compartan características como *Impuestos*, *Gastos de envío*, etc.

Estas **zonas** permitirán una administracíon más fluída y dinámica ya que pueden modificar valores de varias provincias sin tener que hacerlo individualmente.

.. figure:: images/09-configuracion-zonas.png
   :align: center

   Configuración de Zonas (por país y provincias).


.. figure:: images/10-configuracion-zonas2.png
   :align: right

   Crear nueva Zona.


A modo de ejemplo crearemos una *Zona* formada por otras dos *Zonas* previamente creadas.

Nuestra *Zona* a crear se llamará **Norte** y estará compuesta por la *Provincia de Formosa* y por la Zona llamada *Provincias Cercanas*, la cual incluye a *Chaco*, *Corrientes* y *Salta*.

Para ello nos dirigimos a:
::

    Crear > Zona formada por otras zonas

Luego ingresamos un "código" en el campo *Código* y el "nombre" de la Zona (**Norte** en nuestro ejemplo).


.. figure:: images/11-configuracion-zonas3.png
   :align: center

   Datos de *nueva zona*.

.. tip:: El código lo determina el usuario. Recomendamos un criterio lógico para la buena administración.

.. figure:: images/12-configuracion-zonas4.png
   :align: right

   Añadir miembros.

A continuación damos click en *Añadir miembro* y seleccionamos una de las zonas a unir (ej: *Formosa*).

Repetimos la acción seleccionando la otra zona (ej: *Cercanas*). Podríamos agregar más zonas si fuera necesario.

Una vez finalizado le damos click al botón **Crear** y nos debería aparecer un mensaje de *Operación exitosa*.


.. figure:: images/13-configuracion-zonas5.png
   :align: center

   Nueva Zona creada correctamente!.

Finalmente encontraremos la *nueva zona* llamada **Norte** , en la lista de Zonas.

.. figure:: images/14-configuracion-zonas6.png
   :align: center

   Lista de Zonas.


.. _Monedas:

Monedas
*******

La moneda **Peso argentino** se entrega configurada por defecto.

Usted puede agregar **Monedas** como por el ejemplo el dólar u otras, en los casos que requiera.

Basta con ingresar a **Crear** y seleccionar en el desplegable la moneda que desee.

.. figure:: images/15-configuracion-moneda.png
   :align: center

   Monedas.

.. warning:: Podrá agregar, pero no podrá **quitar** monedas.



.. _Tasas de cambio:

Tasas de cambio
***************

Para establecer una tasa de cambio ustede debe ingresar en **Crear** e indicar la moneda de origen y la de destino, luego asignar la tasa para la conversión.

.. figure:: images/16-configuracion-cambio.png
   :align: center

   Nueva tasa de cambio.


Una vez realizado este proceso la tasa de cambio permanece en el valor asignado. En casos de cambio del valor de la moneda deberá ajustar nuevamente este parámetro.


.. figure:: images/17-configuracion-cambio2.png
   :align: center

   Tasa de Cambio confirmada.


.. warning:: Sea cuidadoso al indicar el múltiplo por el que debe ser alterada la primer moneda para convertirse en el valor nominal de la segunda.


.. _Idiomas:

Idiomas
*******


El lenguaje **Español argentino** se entrega configurado por defecto.

Usted puede agregar **Idiomas**.

Basta con ingresar a **Crear** y seleccionar en el desplegable el idioma que desee agregar.

.. figure:: images/18-configuracion-idioma.png
   :align: center

   Idiomas.

.. note:: Se le habilitará la opción de agregar información de los productos en el idioma agregado, entre otras características.



.. _Modos de pago:

Modos de pago
*************

Usted puede agregar un **Método de Pago** haciendo click en **Crear** y seleccionando alguna opción.

Por ejemplo *Desconectado* para agregar un método de pago que no se realice vía internet.

.. figure:: images/19-configuracion-metpago.png
   :align: center

   Modos de pago.

Una vez dentro uste deberá indicar un código, asignar un orden y activarlo.

También debe seleccinar el/los canales habilitados.


.. figure:: images/20-configuracion-metpago2.png
   :align: center

   Datos para el nuevo modo de pago.

Por último tiene que indicar un nombre, una descripción e instrucciones para que el cliente realice el pago.

.. figure:: images/21-configuracion-metpago3.png
   :align: center

   Detalles para el cliente.

Finalmente se observa el nuevo modo de pago en nuestra lista.

.. figure:: images/22-configuracion-metpago4.png
   :align: center

   Nuevo modo de pago **activado**.

.. nota:: Para métodos de pagos no listados contacte al desarrollador visitando la sección `ayuda <contacto.html>`_ 



.. _Métodos de envío:

Métodos de envío
****************

Para incluir un **Método de Envío** ingrese a **Crear** y asígne un código, un nombre, una descripción y habilite el/los canales para el nuevo método.

.. figure:: images/23-configuracion-metenv.png
   :align: center

   Métodos de envío.

.. figure:: images/24-configuracion-metenv2.png
   :align: center

   Nuevo método de envío.

.. figure:: images/25-configuracion-metenv3.png
   :align: right

   Importe a abonar en concepto de *transporte*.


Luego agregue los impuestos (si se aplican) y la tarifa por el transporte (plana o por producto). Luego presione el botón **Crear**



Finalmente visualizará su nuevo método de Transporte en su lista.


.. figure:: images/26-configuracion-metenv4.png
   :align: center

   Método nuevo **Activado**.



.. _Categorías de envío:

Categorías de envío
*******************

Aquí podremos designar una categoría a los envíos. Por ejemplo: terrestre, acuático, aéreo. La cual luego podremos asignar a nuestros **Métodos de envío**.

.. figure:: images/27-configuracion-catenv.png
   :align: center

   Categorías de envío.


Simplemente debemos crear una nueva **Categoría de envío** y designar un código, un nombre y una descripción.




.. _Categorías de impuestos:

Categorías de impuestos
***********************

Aquí podremos designar una categoría a los impuestos. La cual luego podremos asignar a nuestras **Tasas de Impuestos**.

.. figure:: images/28-configuracion-catimp.png
   :align: center

   Categorías de Impuestos.


Simplemente debemos crear una nueva **Categoría de Impuestos** y designar un código, un nombre y una descripción.


.. hint:: Puede ingresar la categoría del Impuesto al Valor Agregado, ya que luego la necesitará para incorporar la **Tasa de Impuesto**.


.. _Tasas de impuestos:

Tasas de impuestos
******************

Para agregar una nueva tasa de impuestos ingrese a **Crear** y complete el formulario con los datos requeridos.

.. figure:: images/29-configuracion-imp.png
   :align: center

   Tasas de Impuestos.


Finalmente veremos la lista de los impuestos configurados.

.. figure:: images/30-configuracion-imp2.png
   :align: center

   Lista de Impuestos.


.. _Administradores:

Administradores
***************

.. danger:: Este ítem ya se encuentra configurado por el desarrollador. Es imperativo no modificar esta sección por cuestiones de seguridad ya que podría comprometer seriamente el sistema y su información privada.

