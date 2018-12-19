# crecimiento-poblacion-andalucia
Datos y descripción del mapa interactivo para conocer el crecimiento de la población en los municipios de Andalucía
La base de datos está extraida del Istituto de Estadística y Cartografía de Andalucía http://www.juntadeandalucia.es/institutodeestadisticaycartografia
y la base cartográfica del mapa de Arcgis.com https://www.arcgis.com/home/item.html?id=7235c0896d9f4f93939f4fd18d512882

LIMPIEZA DE DATOS
Me dí cuenta que algunas poblaciones no aparecian los datos del crecimiento o descenso de la población y 
fue porque el campo texto tenía diferencia en la descripción de los municipios, por ejemplo, las ñ o que 
algunas habían desaparecido en la tabla que copie de nacimientos, o los  municipios con artícuos, (El), (Los)... 
en la otra tabla aparecía sin paréntesis. También la tabla de nacimientos aparecía con (Capital) las capitales de provincia, etc.

VISUALIZACIÓN
En tableau trabajé siguiendo estos pasos:
En medidas arrastré "Crecimiento Natural a Dimensiones" y la volví a arrastrar a colores.
Edité los colores de discreto a continuo en un rango de 10 pasos, en una gama de rojos para pérdida de población y verde para ganancia.
Arrastré Texto (los nombres de los municipios a Texto) municipio a Detalles, cabiando el nombre a Municipio.
También lo añadí a filtro con la opción de "Mostrar resaltador" edité también a nombre de "Municipio"

# El resultado está publicado en tableau public: https://public.tableau.com/profile/sevilla.hoy2252#!/vizhome/CrecimientodelapoblacinenAndaluca2017/Dashboard1
