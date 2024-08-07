# Changelog-Favalogyc
Registro e historial de cambios y actualizaciones del proyecto FAVALOGYC

## Versión Front: 01.f6.16.5
## Versión Back: 01.03.01 
### 30/3/23
#
### **Added** (Se agregó)
- Filtro de *Etapa y Articulo* en Trazabilidad
- Boton de *Trazabilidad* en CUPA
- Strock de Sucursal en Alta Manual
- Mensaje de Contraseñas vencidas en el *Login*
- Cartel de *Anulados* en Lotes

### **Changed** (Se cambio)
- *Items per page: 500* en Crear Lotes
- En *Comprobantes* te muestra la lista de Articulos 
- Limite del Calendario (31/12/2099) del filtro de Crear Lote
- Cambio de nombre al boton "Eliminar Pedido" por *Anular Pedidos* en Ver Pedido
- Que los usuarios solo puedan *editar* pedidos/articulos en etapa *Inicial* 

### **Fixed** (arreglado)
- Se corrigio el error que no se mostraban las *Notificaciones*
- El *Boton de descargar* las Notificaciones
- El *cambio de estado* de las Notificaciones (marcar visto"/ "procesar)
- Flechas para ordenar filas de Trazabilidad
- El Boton de *Items per page* de Trazabilidad
- Bug en Comprobanantes *Anulados* que se podian editar como usuario de Empaque
- Navegador por Remitos 
- Observaciones de los PDF de Ordenes de Distribucion

### **Breaking** (se quito)
- Se quito el *Servicio de notificaciones* en usuarios de *Empaque* 

---
## Versión Front: 02.f6.17.4 
## Versión Back: 01.03.02
### 14/4/23
#      
### **Added** (Se agregó)
- La posibilidad de recargar componentes si fallan servicios en sección *Pedidos*
- Snack Bar si al recargar los componentes vuelven a fallar los componentes en *Pedidos*
- Pop-Up en *Control Darsena y Estanteria*, cuando hay errores en las ordenes

### **Changed** (Se cambio)
- El formato para mantener fijas las cabeceras de las columnas en las tablas 
- Aumento el tamaño del icono rojo de Info (!)
- Los nombres de VENTAS por *ENVÍO A DOMICILIO* y  el de VENTAS SUCURSAL por *RETIRA SUCURSAL* en *EMPAQUE* 

### **Fixed** (arreglado)
- Problema de los Scrolls fijos al pasar de pagina
- Se bloqueó el botón de *Eliminar Selec* en *Agregar Remitos* 

---
## Versión Front: 03.f6.19.2 
## Versión Back: 03.04.01 
### 19/5/23
#      
### **Added** (Se agregó)
- Servicios correspondientes a la logica de *VENTA EN VERDE* en *Empaque*
- *Punto verde* pegado a los codigos de articulo con nombre comenzado en "*FVER*" 
- Filtro para que nunca se muestren las *VeV PROVEDOR* en *CREAR LOTE*
- Logica para evitar que se mezclen los articulos "Comunes" con los *FVER* en *EMPAQUE*
- Icono que aparece cuando se seleccionan articulos *VeV* en *EMPAQUE*
- Filtros de *VeV PROVEEDOR* y *VeV CEDIS* en seccion de *COMPROBANTES*
- Campana de notificaciones en *Comprobantes, Articulos*
- Servicio de Buqueda en *Remito -> Ver Remito* 

### **Changed** (Se cambio)
- Servicio de combo de *TIPOOS DE PEDIDOS* en *CREAR LOTE*, *CREAR REMITO*, *REMITO* y *CREAR DISTRIBUCION*
- Servicio de *Anular Remito* de *Venta Sucursal* de *Reposicion*
- Se quito el boton para *Ordenar por Etapas* en *Pedidos*

### **Fixed** (arreglado)
- Problema con las listas en *Crear Lotes*, que traia 50, en vez de 500
- Buscador en *ORDENES DE DISTRIBUCION* -> *VER ORDEN*, no buscaba por *Codigo de Articulo*
- *BUSCADOR* del modal de *Agregar remitos*
- Boton para ordenar por *Direccion* en seccion de *Notificaciones*

---
## Versión Front: v04.f6.20.9
## Versión Back: v04.05.01 
### 13/7/23
#      
### **Added** (Se agregó)
- Posibilidad de que usuarios de distintas Sucursales puedan acceder al programa de Vta. Telefónica
- *Guía de OCA* para los pedidos *VeV Proveedor*
- Teléfono del cliente en los *Datos de entrega* de pedidos *Retira Sucursal*
- *Pedidos VeV* que poseen *MARMADO* y sean de *Mar del Plata*, siempre son *VeV CEDIS*
- Botón *Pasar a la siguiente etapa* para los pedidos *VeV Proveedor* con usuarios *Admin* y *AuxiliarVV* 
- Columna de *Precio de venta* en *Artículos* de *Alta Manual*
- Carteles de ETAPA de *AVISO PRO* y *ENTREGA PRO*  

### **Changed** (Se cambió)
- Las ventas *Retira Sucursal* muestran los *Datos del Cliente*, ya no de la sucursal
- Foco en el buscador al abrir la ventana de *Buscar Artículos*
- Al presionar *ESC* se cierra la ventana de *Buscar Artículos*
- Aumento de la cantidad de Ítems de a ventana de *Buscar Artículos*
- Al presionar  *Enter* en *Alta Manual* no se confirma el pedido
- Validación en el botón *Modificar* en *Crear remito* y *Crear Lote*

### **Fixed** (arreglado)
- La funcionalidad de *Ordenar por cantidad de Artículos* en *Remitos*
- Remitos VeV, no devolvía el Pop-Up con datos automáticos al ser creado.

### **Breaking** (se quitó)
- Artículos inhabilitados de la *BDD* de *ALTA MANUAL*

---
## Versión Front: v05.7.1.0 
## Versión Back: 05.01.04  
### 7/08/23
#      
### **Added** (Se agregó)
- Se incorporo en *ALTA MANUAL* el sub-menu de *COMPROBANTE CON REFERENCIA FACTURA* 
- Un nuevo servicio para búsqueda de Facturas para la Pantalla de *CBTE CON REFERENCIA FACTURA*
-  En *VER REMITO*, se agrego al servicio que devuelve los cbtes de un remito, el "Tipo de Pedido"

### **Changed** (Se cambió)
- Se dividio el *ALTA MANUAL* en sub-menus con los distintos tipos de pedidos: *CBTE SIN REFERENCIA FACTURA, PRÉSTAMO, TRANSFERENCIA CLIENTE INTERNO*

### **Fixed** (arreglado)
- El boton que ordena por fechas los comprobantes en *PEDIDOS*
- Se corrigió un bug que había en *Comprobantes, Pedidos, suc. EMPAQUE*, que al aumentar la cantidad de comprobantes en la tabla, los ordenaba por estado.
- En *VER REMITO* un bug en el buscador, que solo buscaba cuando se le aplicaba el número entero del buscador.

### **Breaking** (se quitó)
- En pedidos REPOSICION se quitó la validación por stock en los artículos que comienzan con: *'M999', 'MWEB', 'FBIN', 'FMIL', 'MDOR', 'MPIE', 'MSUA’*
- Para *COMPROBANTE CON REFERENCIA FACTURA* en *ALTA MANUAL* se quito la funcionalidad de resguardo de información. Ademas, se sacaron los botones de refrescar stock y agregar artículos

---
## Versión Front: v6.7.3.0 
## Versión Back: v06.01.04
### 25/8/23 
#  
### **Added** (Se agregó)
- Para *COMPROBANTE CON REFERENCIA FACTURA* en *ALTA MANUAL* un servicio de búsqueda de facturas o DNI, el cual trae los datos de: “Nro de Factura, Fecha de Emisión de Factura, Codigo de Cliente y Razón Social del Cliente". Este servicio busca por DNI y por comprobantes (completo,  últimos dígitos o reducido)
- Se aplicó una condición para que en el detalle de cada artículo se visualice la “Cantidad máxima” y la “cantidad a programar”, esta última nunca va poder ser menor a 1 ni superar a la máxima.
- Se realizó la logica para que los pedidos de *COMPROBANTE CON REFERENCIA DE FACTURA*, remitan al igual que un pedido tipo *VENTA* 

### **Changed** (Se cambió)
- *COMPROBANTE CON REFERENCIA FACTURA* en *ALTA MANUAL* el detalle de “Stock Sucursal” fue quitado y  “Stock Cedis” pasó a llamarse *“Cant máxima”*
- En *VER REMITO* se modificó el nombre de “Imprimir” por el de “Reimprimir”.
- En *VENTA TELEFONICA*, ahora se puede modificar los datos de entrega. 
- Para los pedidos *VEV PROVEEDOR* se quito el boton de “Reimprimir” en *VER REMITO*

### **Fixed** (arreglado)
- Se corrigió un bug que “rompía” la pantalla durante los segundos en que los servicios cargaban

---
## Versión Front: v07.7.3.4
## Versión Back: v07.01.02
### 18/9/23  
#  
### **Fixed** (arreglado)
- Bug en el Checkbox de ACTIVOS de *PEDIDOS*
- Los pedidos tipo “Transferencia Cliente Interno”, pueden crear Zunchos
- Lógica del traqueo con los artículos que poseen muchas partes, tambien se incorporo esta lógica en CONTROL AUTOMATICO.

### **Breaking** (se quitó)
- Se quitó la precarga en el alta manual para los *COMPROBANTE CON REFERENCIA FACTURA* en *ALTA MANUAL*

---
## Versión Front: v8.7.4.3 
## Versión Back: v08.01.02
### 2/10/23  
#  
### **Added** (Se agregó)
- Nuevo rol: test.auxiliarvv que posee los permisos especiales para cambio de etapa de las "Venta en Verde Proveedor"
- Nueva solapa para realizar el cambio de etapa de las "Venta en Verde Proveedor", además, se agregó servicio para cambiar la etapa POR ARTÍCULO.

### **Fixed** (arreglado)
- Bug en solapa de trazabilidad que no cargaba
- Trazabilidad al generar número de envio de OCA y envío de Mail.
- Bug en NOTIFICACIONES.

---
## Versión Front: v09.7.6.1
## Versión Back: v09.01.05
### 31/10/23  
#  
### **Added** (Se agregó)
- Spinners en distintas partes te la aplicación:
    - Ver pedido/ Datos de Entrega/ lapiz 
    - Ver pedido/ CUPA/ Imprimir
    - Crear lote/ lápiz
    - Ver lote/ Imprimir Cupa
    - Crear remito/ lápiz 
    - Orden de Distribución (despachada)/ Descargar COT
    - Orden de Distribución/ Descargar Excel
    - Ver Orden de Distribución/ Descargar Exce
- En Alta Manual (Reposición) se aplicó validación para que CANTIDAD no supere a STOCK CEDIS.
- Depósito especial para ventas y reservas para los artículos VeV. Estos depósitos son el “95” y el “VV”
- Pedidos / Comprobantes / Con Referencia de Factura / Ver Pedido, se creo un campo con el número de factura original.

### **Changed** (Se cambió)
- Estilo de los componentes deshabilitados:
    - Ver Pedido -> Tipo y Comprobante
    - Crear Lote y Crear Remito-> input de Fecha de entrega
    - Crear Lote, Lotes, Crear Remito, Remitos -> Inputs de los filtros de "Fecha desde y hasta"
    - Ver Lote / Botón Editar Lote -> Inputs de Fecha y cantidad de artículos
    - Botón Crear remito -> Alias, Cant remitos, número desde y hasta
    - Crear Orden Distribución/Botón Crear O.D -> Input cantidad de remitos
    - Ver Orden de Distribución / Botón Editar -> Input Cantidad de remitos y el de fecha
    - Artículos / Partes de artículos / Modificar Partes -> Inputs Código artículo, nombre y descripción
    - Artículos / Códigos de barras / Seleccionar / Editar -> Código artículo y nombre
    - Artículos / Códigos de barras / Seleccionar / Agregar->  Código artículo y nombre.
- En EMPAQUE, se optimizó la velocidad del servicio que trae los pedidos.
- En los pedidos de EMPAQUE de VENTA EN VERDE que contienen artículos comunes, se hizo un arreglo para seleccionar por artículo.
-En EMPAQUE, el servicio que trae los comprobantes a programar, primero traiga los A PROGRAMAR y luego los PROGRAMADOS.
- Pedido / abrir / Datos de entrega se puede editar los datos de entrega por artículo.
- En Pedidos / Comprobantes / ARTÍCULOS, solo se traen artículos en etapa INICIAL - LOTE - ESTANTERIA - DÁRSENA - AVISO PROV, es decir, los ACTIVOS
- Los botones de Imprimir CUPA y el de ELIMINAR SELEC, cambian de color luego de seleccionar un check.

### **Fixed** (arreglado)
- Bug en el orden por 'Fecha de emisión’ en EMPAQUE
- Bug que cuando se ordena la tabla se rompía botón de notificaciones.
- Cuando no haya stock, y se quiera agregar el artículo a CBTE CON REF FACT, no de error.

### **Breaking** (se quitó)
- En Empaque se quitaron aquellos pedidos que devuelven cantidad negativa en el campo de “cantArticulos”.

---
## Versión Front: v10.0.0.6 
## Versión Back: v10.02.02
### 29/11/23  
#  
### **Added** (Se agregó)
- Pantalla de FACTURAS y servicio que trae facturas de Tango
- Colores a distintos ESTADOS de las facturas
- Pantalla de FACTURA DETALLE
- Boton VER para dirigirse a FACTURA DETALLE
- En CONTROL DE CARGA, se agrego un control de Front-end para chequear el CUPA en la lista de pantalla para avisar que se equivocó

### **Changed** (Se cambió)
- Después de programar un pedido EMPAQUE, la app no te dirija a Pedidos-> Comprobantes, se dirige a EMPAQUE nuevamente.
- En ORDEN DE DISTRIBUCIÓN, se ve la fecha de distribución y no la de alta.
- Se optimizó el tiempo de respuesta de los servicios en ORDEN DE DISTRIBUCIÓN. 

### **Fixed** (arreglado)
- Correcciones en las impresiones de órdenes de distribución (VER ORDEN)  

---
## Versión Front: v10.0.0.6 
## Versión Back: v10.02.03
### 12/12/23  
# 
### **Added** (Se agregó)
- Notificacion VISTO y PROCESADO en TRAZABILIDAD
- Validaciones para evitar acciones en pedidos que contengan NOTIFICACIONES sin ser PROCESADAS.

### **Fixed** (arreglado)
- Cantidad de registros en VER FACTURAS al filtrar

### **Breaking** (se quitó)
- Trazabilidad cada vez que se genere PDF de Orden de Distribución 
- Trazabilidad cada vez que se genere PDF de Remito

---
## Versión Front: v11.0.0.4 
## Versión Back: v11.01.01
### 02/01/24  
# 
### **Added** (Se agregó)
- Control desde el Frontend para validar que todos los artículos están controlados, antes de llamar al servicio del Backend, en CONTROL DE CARGA -> CONTROLAR ORDEN

### **Changed** (Se cambió)
- Tiempo de respuesta del listado de CONTROL DE CARGA
- Tiempo de respuesta del listado de CONTROL DE SECTOR
- Lógica de traqueo del CUPA, evitando la actualización continua, en CONTROL DE CARGA -> CONTROLAR ORDEN
- Llamado al servicio sólo cuando se cargue por primera vez el listado detalle de artículos a controlar, en CONTROL DE ESTANTERÍA/ DÁRSENA

### **Fixed** (arreglado)
- Visualización del spinner en CONTROL DE ESTANTERÍA Y DÁRSENA

---
## Versión Front: v12.0.01 
## Versión Back: v12.01.04
### 07/03/24  
# 
### **Changed** (Se cambió)
- En CONTROL DE CARGA cuando el usuario tráquea remitos mixtos (con ZUNCHO/ sin ZUNCHO), no se realiza el traqueo automático de la TOTALIDAD de la orden al traquear un pedido con zuncho.
- Velocidad al generar ÓRDENES DE DISTRIBUCIÓN.

### **Fixed** (arreglado)
-  Errores ortográficos. 
- FILTROS de ÓRDENES DE DISTRIBUCIÓN.
- SERVICIO de  IMPRIMIR ORDEN DISTRIBUCIÓN.
- Bug al anular un remito de Comprobante Sin Referencia Factura.

---
## Versión Front: v13.0.3
## Versión Back: v13.01.04
### 25/03/24  
# 
### **Added** (Se agregó)
- Un botón de TRAZABILIDAD, para poder ver  aquellos pedidos RETIRA SUCURSAL que siguen en la sección de EMPAQUE y su estado en FAVALOGYC.

### **Changed** (Se cambió)
- En DATOS DE ENTREGA, se limitó la cantidad de caracteres del campo de TELÉFONO a 17 caracteres y se agregó una leyenda para notificar al usuario que excedió el límite.
- En ÓRDENES DE DISTRIBUCIÓN, se realizaron modificaciones para que las ordenes del año 2099, se vean últimas en el listado (ORDER BY).

### **Fixed** (arreglado)
- En ÓRDENES DE DISTRIBUCIÓN, no se actualizaban las fechas de entrega al EDITAR.
- En CONTROL DE ORDEN, problema de los códigos de barra duplicados.

---
## Versión Front: v14.0.4
## Versión Back: v14.01.02
### 14/05/24  
# 
### **Added** (Se agregó)
- En DATOS DE ENTREGA (Pedidos-> Comprobantes-> Abrir) se creó el botón de CAMBIO DE ETAPA, con el cual se pasan los pedidos de INICIAL -> AVISO PRO -> ENTREGA PRO.
- En DATOS DE ENTREGA, se agrego NÚMERO DE GUIA DE OCA, el mismo aparece cuando se pasa de etapa INICIAL a AVISO PRO, y se visualiza en la solapa de TRANSPORTE.

### **Changed** (Se cambió)
- Apertura de datos de entrega cuando el transporte es OCA. En los casos de ‘Venta Verde’, cuando el pedido tenga distintos proveedores, se le asignaran distintos datos de entrega al pedido.  

### **Fixed** (arreglado)
- Bug en en ORDEN DE DISTRIBUCIÓN, cuando se descargaba el Excel daba el precio actualizado, no el de la fecha en que se realizo la orden.
- En PEDIDOS, el cartel de etapa AVISO PRO y ENTREGA PRO no se visualizaba correctamente.   

---
## Versión Front: v15.0.7 
## Versión Back: v15.01.05
### 06/06/24
# 
### **Added** (Se agregó)
- Un botón para actualizar el estado de los pedidos con transporte OCA. Este se encuentra en PEDIDO -> DATOS DE ENTREGA, y se habilita cuando el transporte del pedido es OCA y esta color rojo, es decir DESACTUALIZADO.
- Espacio en COMPROBANTES -> ARTÍCULOS, en CREAR LOTE, en CREAR REMITO, en CREAR ORDEN DE DISTRIBUCIÓN y en CONTROL DE CARGA, para que aquellos pedidos que tengan transporte OCA, indiquen su estado, es decir, si esta actualizado (verde) y si no está actualizado (rojo).

### **Fixed** (arreglado)
- Corrección para reingresar remitos.

---
## Versión Front: v15.0.7 
## Versión Back: v15.01.05
### 06/06/24
# 
### **Added** (Se agregó)
- Implementación de actualizar nro guia de OCA para usuarios CEDIS. 

### **Fixed** (arreglado)
- Actualización de Nro de guia de OCA en CREAR REMITO.
- En Órdenes de Distribución no aparecían algunos remitos.
- Mover zunchos para los pedidos.
- Corrección cuando zuncho tiene más de un remito, debería figurar con cantidades cero, excepto el último
- En CREAR ORDEN DE DISTRIBUCIÓN en filtro por TIPO fallaba.
- En REMITOS, no funcionaba el FILTRO por TIPO fallaba.



