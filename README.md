# Unidad: El concepto de Modelo en la Inteligencia Artificial (IA)

En esta unidad exploramos el concepto de **modelo** en el campo de la Inteligencia Artificial (IA). Analizamos su definición, los tipos de modelos existentes (simbólicos vs. basados en datos) y cómo se representa el conocimiento para resolver problemas complejos de manera automatizada.

---

### 1. ¿Qué es un Modelo?
Un **modelo** es una representación simplificada de un sistema que nos permite analizarlo y realizar predicciones. En IA, es una estructura matemática que captura las relaciones entre datos de entrada y salidas.

* **Modelo vs. Algoritmo**: El algoritmo es el conjunto de pasos (las "instrucciones"), mientras que el modelo es el resultado del conocimiento adquirido (el "saber hacer").

#### Clasificación principal:
* **Modelos Entrenados (IA basada en datos)**: Aprenden mediante Machine Learning o Deep Learning ajustando parámetros (ej: redes neuronales).
* **Modelos No Entrenados (IA simbólica)**: Se basan en reglas y conocimientos predefinidos por expertos (ej: Sistemas Expertos).

---

### 2. Tipos de Aprendizaje Automático
Dentro de los modelos entrenados, encontramos tres enfoques principales:
1.  **Supervisado**: Entrenado con datos etiquetados (Clasificación y Regresión).
2.  **No supervisado**: Busca patrones ocultos sin etiquetas (Clustering o agrupamiento).
3.  **Por refuerzo**: El agente aprende mediante un sistema de recompensas y castigos.

---

### 3. Representación del Conocimiento: La Jerarquía DIKW
Para que una máquina "entienda", debemos procesar la información según diferentes niveles de profundidad:

1.  **Datos (Data)**: Hechos brutos sin contexto (ej: "38").
2.  **Información (Information)**: Datos con contexto (ej: "La temperatura corporal es de 38ºC").
3.  **Conocimiento (Knowledge)**: Aplicación de reglas (ej: "38ºC indica fiebre").
4.  **Sabiduría (Wisdom)**: Metaconocimiento y toma de decisiones éticas (ej: "Hay que ir al médico").

---

### 4. Sistemas Basados en Reglas (SBR)
Son modelos que utilizan reglas explícitas (**Si... entonces...**) para tomar decisiones. Sus componentes son:

* **Base de conocimiento**: El conjunto de reglas `IF-THEN`.
* **Base de hechos**: La memoria activa con la situación actual.
* **Motor de inferencia**: El "cerebro" que aplica las reglas.
    * **Encadenamiento hacia adelante (Forward chaining)**: Partimos de los hechos para llegar a una conclusión (Razonamiento deductivo).
    * **Encadenamiento hacia atrás (Backward chaining)**: Partimos de un objetivo y buscamos los hechos que lo justifican (Razonamiento inductivo).

---

### 5. Técnicas de Representación Lógica
Para codificar el conocimiento de forma interpretable por la máquina, utilizamos diferentes sistemas formales:

| Técnica | Descripción | Ejemplo |
| :--- | :--- | :--- |
| **Lógica de 1er orden** | Utiliza cuantificadores y predicados. | `∀x (Humano(x) → Mortal(x))` |
| **Lógica Proposicional** | Conecta proposiciones simples con operadores. | `P → Q` (Si llueve, el suelo se moja) |
| **Lógica Difusa** | Gestiona incertidumbres o grados de verdad (entre 0 y 1). | "La temperatura es fresca" (0.75) |
| **Ontologías** | Estructuras jerárquicas de clases y relaciones. | "Un gato es un tipo de mamífero" |

---

### 6. Aplicaciones Reales
Estos modelos se materializan en tecnologías que utilizamos diariamente:
* **LLMs (Large Language Models)**: Como GPT o BERT, para procesar lenguaje natural.
* **Sistemas de recomendación**: Como los de Netflix o Spotify.
* **Visión por computador**: Detección de anomalías en radiografías o vehículos autónomos.
* **Asistentes virtuales**: Siri, Alexa y Google Assistant.

> **Conclusión**: La clave de la IA no es solo tener datos, sino saber cómo representarlos y qué estrategia de resolución (reglas, búsqueda o aprendizaje) es la más eficiente para cada problema.
