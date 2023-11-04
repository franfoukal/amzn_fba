
- [Envio de productos a Amazon](#envio-de-productos-a-amazon)
  - [Pasos](#pasos)
- [Productos defectuosos y devoluciones](#productos-defectuosos-y-devoluciones)
  - [Devoluciones](#devoluciones)


# Envio de productos a Amazon
## Pasos

1. Ir a Inventory > Manage All Inventory > Add Product (btn)

2. Ingresar el ASIN
    * Vender siempre nuevo
    * SKU: identificacion propia nuestra interna
    * Precio
    * Condicion -> nuevo
    * cantidad
    * Tipo de Fulfillment -> FBA
    * Desactivamos Canada y Mexico
    * Guardar
    
3. Elegir opcion `Print and apply Amazon barcodes myself` y continuar

4. Se va a cargar el workflow del shipping plan y la config:

    * __Shipping From:__ Esto es MUY importante, tiene que ser siempre una direccion de USA, por mas que enviemos de china o del 3PL.

        > Influye luego en los courier y en las labels, como en las devoluciones, que siempre vuelven ahí
    
    * __Detalle de packaging__:
        * Unidad individual: Las cajas pueden ser diferentes y se pueden enviar varios SKUs en la misma caja (RECOMENDADO)
        * New template
            * Se le puede poner un nombre
            * Se puede elegir tipos: 
                * __Pallet__ 
                * __Case Pack:__ cada caja debe contener el mismo producto y el mismo numero de unidades en su interior. No se pueden mezclar los SKU. (NO SE RECOMIENDA)

    * __Product Prep And Labeling__: 

        * Para productos con categorias especiales que necesiten alguna preparacion, se pueden revisar las categorias y ver requisitos o pasos.

            > Poner que `No necesita prep`

        * ¿Quien va a pegar los labels?
            * Amazon -> cobra por unidad ($0.55 )
            * Seller -> precio del externo



5. Una vez configurado guardar. Se va a habilitar la casilla para las unidades en el item a agregar.

* Ingresar las unidades a enviar -> `Ready to pack`

* Va a aparecer link con los labels a imprimir -> Con el PDF, mandarselo al encargado del etiquetado - 3PL

* Hay dos tipos de labels, uno para cada unidad individual y otro para la caja final. 
      

> TODO LO QUE LLEGA A AMAZON TIENE QUE ESTAR ETIQUETADO SI O SI


6.  Click en `Pack individual units`, van a aparecer opciones de packaging:
    * Entra todo en una caja

    * Entran en distintas cajas

        > La mayoria de las veces vienen en distintas cajas asi que elegimos esa opción
        * Ponemos la cantidad de cajas que necesitamos y `open web form` 
        * Ponemos cuantas unidades vendran en cada caja, __ESTO SE DEBE COORDINAR CON EL PROVIDER O 3PL__ 

    * Ingresar el peso de las cajas, dimensiones y confirmar


7. Confirmar y continuar

8. Ingresar el `Ship Date` que es un estimativo de cuando llegarian las unidades a amzn, o cuando la despachariamos. Es para organización personal, no influye en nada.

9. Seleccionar `Shipping Mode`:
    * SPD (Small Parcel Delivery): varias cajas sueltas dentro del camion de logistica
    * LTL (Less Than Truckload): Una parcela en rack del camion

10. Seleccionar courier, al principio utilizar el asociado a Amazon (UPS). Aceptar los costos

11. Se van a generar los labels de las cajas finales, es decir de las cajas que enviamos con mercadería hacia amazn. Guardar y enviar al 3PL

12. Luego de esto, amazon nos avisara cuando lleguen y cuando los recepcionen.


> TENER CUIDADO CON LA DIRECCION DE USA



# Productos defectuosos y devoluciones
## Devoluciones

Al realizar el cliente una devolución, por lo general no podremos ponerlo a la venta tal cual vuelve ya que puede estar abierto el packaging u otras causas. 

Nosotros debemos chequear el producto devuelto. 

La idea es que las devoluciones lleguen a una direccion en USA (3PL en nuestro caso). 

> Hay veces que una devolucion es mas costoso conservarla, procesarla y almacenarla que desecharlo