# Análise Comparativa de Algoritmos de Machine Learning para Predição de Doenças Cardiacas

Esse projeto teve como objetivos analisar as predições resultantes de 5 modelos de Machine Learning:

* Regressão Lógistica;
* Máquina de Vetores de Suporte;
* K - Elementos mais Próximos;
* Árvore de Decisão;
* Floresta Randomica;

> O desafio em questão era um problema de categorização onde cada modelo deveria predizer se, dado um conjunto de features, tais como idade, batimento cardiaco e sexo, qual a chance de uma pessoa possuir uma doença cardiaca.

* Como métodos e metricas de avaliação dos modelos foram usados:
    * F1-Score;
    * Matriz de Confusão;
    * Curva ROC AUC;
    * Acuracia;

* Para uma maior análise e obtenção de resultados todos os modelos testados usaram hiperparamertros. Além disso,, para melhor análise das metricas utilizada, cada modelo executo e gerou a média f1-score 30 vezes. E desse resultado foram gerados alguns testes:

    * Normalidade;
    * Friedman;
    * Homocedasticidade;
    * Post Hoc;
    * Nemeyin;

* Por fim, também foi realizado a análise das curvas de ROC AUC

### DataSet Utilizado

* [Heart Failure Prediction Dataset](https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction/code?datasetId=1582403&sortBy=voteCount)

### Autores
* Renan Nicolau Gomes
* Jonas Renan Morais de Lima

### Objetivo Especifico
 * Esse projeto surgiu na disciplina de Reconhecimento de Padrões (Machine Learning) e teve como objeto especifico servir como forma de avaliação para a segunda verificação de aprendizagem. Seu docente é o professor Dr. Michael Cruz.

 ### Alguns comando antes de abrir o projeto na sua IDE de preferencia

 ```bash
    python -m venv venv
    venv\script\active
    pip install -r package.txt
 ```


