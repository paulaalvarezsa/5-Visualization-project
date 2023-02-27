
# The influence of the environment on the purchase of erotic toys

Un analisis sobre las ventas de una tienda online de juguetería para adultos que vende en Europa, México y Chile.

- [@paulaalvarezsa](https://github.com/paulaalvarezsa)

![sex_toys_picture.jpeg](https://github.com/paulaalvarezsa/ventas_juguetes_adultos/blob/main/sex_toys_picture.jpeg)

## Hipótesis
**¿Influyen en las ventas** de juguetería erotica los precios del **barril de petróleo** y/o la **posición de la luna**?

Cabría pensar que en la juguetería para adultos, el entorno influye en la toma de decisiones de compra, siendo un producto que no es de primera necesidad y que el estado de ánimo podría ser impulsor de la compra.

El año 2022 ha sido un año muy marcado por la inestabilidad economica en la que paises como UK o España que no estaban acostubrados a ello han vivido inflacción, y sus ciudadanos perdida de poder adquisitivo.

El precio del **barril de petróleo** ha sufrido subidas diarias ¿Ha influido esto en la decisión de compra de productos de juguetería erótica?

¿Puede que la **posición de la luna** haya influido en los días que los adultos han decidido invertir en su vida erótica comprando juguetes?

## Proceso de analisis

Recogida y limpieza de datos para la elaboración de las siguientes 3 tablas:




| Tabla | Tipo     | Description                |Método|
| :-------- | :------- | :------------------------- |:-------  |
| moon_fases | CSV |  Fases de la luna por día en el año 2022. |Scraping |
| sales | CSV | Ventas diarias del año 2022 de juguetes eroticos | Aportada por la empresa.
|  oil| CSV| Precio diario del barril "Oil Brent" en el año 2022 |CSV de URL |



## Descubrimientos

![facturacion_preciobarril.png](https://github.com/paulaalvarezsa/5.Visualization-project/blob/main/fotos/facturacion_preciobarril.png)

![Facturacion_diasdeluna.png](https://github.com/paulaalvarezsa/5.Visualization-project/blob/main/fotos/Facturacion_diasdeluna.png)

![precio_barril_por_faselunar.png](https://github.com/paulaalvarezsa/5.Visualization-project/blob/main/fotos/precio_barril_por_faselunar.png)


## Conclusiones

Se puede ver una correlación entre las subidas y bajadas del precio del barril y la facturación en la segunda mitad del año.

Las fases de la luna no parecen influir en las ventas mientras que de hacerlo la fase que más ha coincidido con la subida de facturación es la luna nueva.