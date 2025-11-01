# LABORATORIO-2
Integrantes: Mateo Bedoya, Juan Pablo Clavijo, Valeria Piedrahita.

### 1. Análisis estadístico.
¿Cuál es el promedio, mínimo y máximo de los atributos base (HP, Attack, Defense, Speed) de todos los Pokémon? 
 <img width="278" height="136" alt="image" src="https://github.com/user-attachments/assets/a7b427d9-4362-496c-9317-5876835c6c96" />

### 2. Análisis gráfico 
Cree un histograma para visualizar la distribución de los valores de 
Base Exp.
<img width="695" height="472" alt="image" src="https://github.com/user-attachments/assets/4a4f8d9b-8519-4094-a098-913a2a4765c1" />

Interprete si la distribución es simétrica o sesgada. 
La distribución de la experiencia base está sesgada positivamente.Esto indica que la mayoría de los Pokémon otorgan una cantidad moderada de experiencia al derrotarlos,y solo un grupo reducido proporciona mucha más (por ejemplo, Pokémon legendarios o de etapas finales).

### 3. Análisis gráfico 
Realice un boxplot comparando los valores de Attack Base entre los tipos principales (Type1). Identifique qué tipo tiene Pokémon con ataques más altos en promedio. 
 <img width="1005" height="584" alt="image" src="https://github.com/user-attachments/assets/e983b1c8-9683-455a-8df3-e90d1db658ce" />
 
En promedio, los Pokémon de tipo Dragon poseen los ataques base más altos, seguidos de los tipos Fighting y Ground, mientras que los tipos Fairy y Bug tienden a tener los valores más bajos.
### 4. Análisis estadístico 
¿Cuál es el top 5 de especies (Species) más frecuentes en el dataset? 
<p>Especie</p>  
<p>Paradox Pokémon    22</p> 
<p>Mouse Pokémon      14</p> 
<p>Fox Pokémon         9</p>
<p>Dragon Pokémon      9</p>
<p>Pumpkin Pokémon     8</p> 

### 5. Análisis gráfico 
Genere un gráfico de barras que muestre la cantidad de Pokémon por 
tipo principal (Type1). ¿Qué tipo es el más común?
<img width="850" height="584" alt="image" src="https://github.com/user-attachments/assets/b34308dc-78f2-40d2-ae97-718066a3f564" />
El tipo Water (Agua) es el más frecuente en el dataset de Pokémon (Type1)

### 6. Análisis estadístico 
Calcule la correlación entre los atributos HP Base, Attack Base, Defense Base y Speed Base. ¿Qué atributos están más correlacionados entre sí? 

Los atributos más correlacionados entre sí son Attack Base y Defense Base (r ≈ 0.47), seguidos de Attack Base y HP Base (r ≈ 0.46).Los atributos de ataque y defensa presentan una correlación moderada, lo que sugiere que los Pokémon con alto ataque suelen tener también una defensa superior. En cambio, la velocidad es un atributo más independiente del resto.

### 7. Análisis gráfico 
Cree un heatmap (mapa de calor) con la matriz de correlaciones obtenida en el punto anterior. Interprete los resultados.
<img width="527" height="451" alt="image" src="https://github.com/user-attachments/assets/32b28fcd-72ff-4710-9c48-a9eadcf7750b" />

El mapa de calor muestra una correlación moderada positiva entre Attack Base, Defense Base y HP Base, lo que indica que los Pokémon con mayor ataque suelen tener también buena defensa y puntos de vida.

Por el contrario, Speed Base presenta una correlación débil con los demás atributos, evidenciando que la velocidad es una característica más independiente dentro de las estadísticas base.
 
### 8. Análisis gráfico 
Realice un diagrama de dispersión (scatter plot) entre Weight_kg y Attack Base. ¿Existe relación entre el peso de un Pokémon y su capacidad de ataque? 

 <img width="695" height="550" alt="image" src="https://github.com/user-attachments/assets/56d34076-010d-443c-8bab-4a71bc98104a" />

El diagrama muestra que no existe una relación clara entre el peso del Pokémon y su poder de ataque.Los puntos se encuentran ampliamente dispersos, sin una tendencia ascendente definida.

Aunque algunos Pokémon más pesados presentan ataques altos, en general la correlación entre ambas variables es débil, indicando que el peso no influye significativamente en la capacidad ofensiva.
### 9. Análisis estadístico 
Determine el promedio de altura y peso por tipo principal (Type1).Interprete cuál tipo tiende a tener Pokémon más grandes. 

Los resultados muestran que los Pokémon de tipo Steel, Ground y Dragon presentan los promedios más altos de peso y altura, por lo que tienden a ser las especies más grandes y pesadas.

En contraste, los tipos Bug, Grass y Fairy registran los valores promedio más bajos, indicando que suelen estar compuestos por Pokémon pequeños y ligeros.
 
### 10. Análisis gráfico 
Construya un gráfico de violín o boxplot múltiple comparando el atributo Speed Base entre los tipos Flying, Electric y Ground. ¿Qué tipo de Pokémon tiende a ser más rápido?

<img width="695" height="548" alt="image" src="https://github.com/user-attachments/assets/61ab84cb-8152-441a-9f1e-d8b7fd270996" />

El gráfico muestra la distribución del atributo Speed Base entre los tipos Electric, Flying y Ground.
Se observa que los Pokémon de tipo Electric presentan las velocidades base más altas en promedio, seguidos por los de tipo Flying, mientras que los de tipo Ground son, en general, más lentos.
