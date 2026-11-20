# 🌸 Análise Exploratória de Dados: Base Iris

Este projeto realiza uma análise exploratória e estatística do clássico conjunto de dados **Iris**, utilizando Python no Google Colab. O objetivo é compreender a distribuição das espécies e identificar os padrões morfológicos que as diferenciam. Para o projeto trilha.


## 📊 Sobre o Conjunto de Dados
O *dataset* Iris contém **150 amostras** divididas igualmente entre três espécies de flores do gênero *Iris* (**Setosa**, **Versicolor** e **Virginica**), com 4 medidas morfológicas (em centímetros) para cada flor:
* Comprimento da sépala (`sepal length`)
* Largura da sépala (`sepal width`)
* Comprimento da pétala (`petal length`)
* Largura da pétala (`petal width`)

## 🔍 Principais Perguntas e Conclusões

1. **Como as espécies estão representadas na base?**
   * A base é perfeitamente balanceada, contendo exatamente **50 registros** para cada uma das três espécies.

2. **Quais características das pétalas melhor diferenciam as espécies?**
   * O **comprimento da pétala (`petal length`)** é a característica que mais evidencia a separação entre os grupos. O desvio padrão dentro de cada espécie é baixo, enquanto as médias e medianas são bem distantes entre si (isolando especialmente a *Setosa* das demais).

3. **Existe relação entre o comprimento da sépala e o comprimento da pétala?**
   * **Sim.** No geral, há uma forte correlação positiva (**0,87**), indicando que flores com sépalas maiores tendem a ter pétalas maiores. Analisando por espécie, essa relação é forte na *Virginica* (**0,86**) e na *Versicolor* (**0,75**), mas fraca na *Setosa* (**0,27**), cujas pétalas mantêm um tamanho pequeno e constante.

## 🛠️ Tecnologias Utilizadas
* **Python 3**
* **Pandas** (manipulação e análise estatística dos dados)
* **Scikit-learn** (importação do dataset)
* **Seaborn & Matplotlib** (visualização de dados com Boxplot e Scatterplot)
* **Google Colab** (ambiente de desenvolvimento)

## 🚀 Como visualizar ou executar
* Você pode visualizar o notebook completo diretamente aqui no GitHub clicando no arquivo `aula_dados.ipynb`.
* Para executar ou editar o código, basta abrir o arquivo no [Google Colab](https://google.com).
