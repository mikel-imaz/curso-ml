---
marp: true
theme: gaia
---

<!-- Global style -->
<style>
section {
  background: #FFFFFF;
}
</style>

<!-- Scoped style -->
<style scoped>
section {
  display: flex; flex-direction: column; justify-content: center; height: 100vh;
}
h1 {
  text-align: center;
}
h2 {
  text-align: center;
}
</style>

# MACHINE LEARNING
## La base de la Inteligencia Artificial

---

## Las reglas del juego

![bg 80%](../docs/imgs/atari_1.gif)
![bg 80%](../docs/imgs/atari_2.gif)
![bg 80%](../docs/imgs/atari_3.gif)

---

## Terminología

![bg 60%](../docs/imgs/mermaid-diagram_1.png)

---

## Etiquetador de cosas

![bg 80%](../docs/imgs/draw_003.png)
![bg 80%](../docs/imgs/draw_004.png)
![bg 80%](../docs/imgs/draw_005.png)
![bg 80%](../docs/imgs/draw_006.png)

---

## Receta (programa)

![bg 60%](../docs/imgs/draw_002.png)

---

## Programación tradicional

![bg 70%](../docs/imgs/draw_008.png)

---

## Cambio de paradigma

![bg 70%](../docs/imgs/draw_009.png)

---

## Generalizar con datos nuevos

```
día     dosis
1   ->  28 mg
2   ->  17 mg
3   ->  92 mg
4   ->  41 mg
5   ->   9 mg
..
60  ->  86 mg
```

---

## Clasificación

![bg 50%](../docs/imgs/graph_010.png)

---

## Patrón

![bg 50%](../docs/imgs/graph_011.png)

---

## Modelo SVC

![bg 85%](../docs/imgs/graph_012.png)
![bg 85%](../docs/imgs/graph_012_1.png)

---

## Modelo Árbol de decisión

![bg 85%](../docs/imgs/graph_013.png)
![bg 85%](../docs/imgs/graph_013_1.png)

---

## Validación

![bg 70%](../docs/imgs/graph_014.png)

---

## Validación

![bg 70%](../docs/imgs/graph_015.png)

---

## Algoritmo

![bg 70%](../docs/imgs/draw_010.png)

---

## Algoritmos

![bg 70%](../docs/imgs/mermaid-diagram_2.png)

---

## Caso práctico

![bg 70%](../docs/imgs/draw_021.png)

---

## Media

```
265, 281, 207, 148, 240, 154, 176, 290, 167, 245, 176, 259, 251, 503, 191
```

```
Media --> 236,9 calorías
```
---

## Puntos

![bg 40%](../docs/imgs/graph_001.png)

---

## Aproximaciones

![bg 70%](../docs/imgs/graph_002.png)
![bg 70%](../docs/imgs/graph_003.png)
![bg 70%](../docs/imgs/graph_004.png)

---

## Regresión lineal simple

```
CALORÍAS = ordenada + (pendiente * PESO)
```
```
CALORÍAS = 236,9 + (0 * PESO) => 236,9
```
```
CALORÍAS = 236,9 + (0 * PESO)   ---> RMSE = 84,6
```

---

## Regresión lineal

![bg 70%](../docs/imgs/mermaid-diagram_3.png)

---

## Regresión lineal

![bg 40%](../docs/imgs/graph_005.png)

---

## Regresión lineal

![bg 40%](../docs/imgs/graph_006.png)

---

## Regresión lineal

```
CALORÍAS = 175 + (1,35 * PESO)   ---> RMSE = 48,8
```
```
CALORÍAS = 175 + (1,35 * 88) = 293,8 → 445 – 293,8 ≈ 151
```

|Modelo|	RMSE|	Desviación|
|-|-|-|
|`Valor medio`|	84,6|	208|
|`Regresión lineal simple`|	48,8|	151|

---

## RL múltiple

![bg 50%](../docs/imgs/graph_007.png)

---

## RL múltiple: Plano

![bg 50%](../docs/imgs/graph_008.png)

---

## Regresión lineal múltiple

```
CALORÍAS = ordenada + (pendiente1 * PESO) + (pendiente2 * GRASA%)
```
```
CALORÍAS = 163 + (1,42 * PESO) + (51,9 * GRASA%)   ---> RMSE = 46,9
```
|Modelo|	RMSE|	Desviación|
|-|-|-|
|`Valor medio`|	84,6|	208|
|`Regresión lineal simple`|	48,8|	151|
|`Regresión lineal múltiple`|	46,9|	143|

---

## RL múltiple: Hiperplano

```
CALORÍAS = ord + (pend1 * GRASA) + (pend2 * CARBOHIDRATOS) + (pend3 * PROTEÍNAS)
```
Dibújalo...
![bg 20%](../docs/imgs/draw_020.png)

---

## RL múltiple: Hiperplano

```
Calorías = 143 + (8,9 * GRASA) + (3,9 * CARBOHIDRATOS) + (4,3 * PROTEÍNAS)
```

|Modelo|	RMSE|	Desviación|
|-|-|-|
|`Valor medio`|	84,6|	208|
|`Regresión lineal simple`|	48,8|	151|
|`Regresión lineal múltiple`|	46,9|	143|
|`Hiperplano`|	3,8|	4|

---

## ¿Qué es entonces la IA?

![bg 60%](../docs/imgs/draw_029.png)

---

## ¿Qué es entonces la IA?

![bg 60%](../docs/imgs/draw_030.png)

---

## IA

![bg 70%](../docs/imgs/draw_031.png)

---

## ¿Y por qué ahora?

![bg 70%](../docs/imgs/mermaid-diagram_4.png)