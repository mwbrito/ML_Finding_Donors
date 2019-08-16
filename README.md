
# Finding Donors

## Visão geral do projeto
Projeto desenvolvido durante o Udacity's Machine Learning Engineer Nanodegree, onde são aplicadas técnicas de aprendizado de máquina para resolver um problema de classificação.


Segue abaixo um resumo do pipeline implementado:

* Explorando os Dados
* Preparando os dados
  * Transformação logarítmica
  * Normalização de atributos numéricos
  * Pré-processamento dos dados - one-hot encoding
  * Embaralhar e dividir os dados (train_test_split)
* Avaliando a performance do modelo
  * fbeta_score
  * accuracy_score
* Modelos de Aprendizado Supervisionado com Sklearn
  * KNeighborsClassifier
  * DecisionTreeClassifier
  * AdaBoostClassifier
* Tuning do modelo
* Validação final do modelo
* Extraindo a importância do atributo


## Requisitos de software

Este projeto utiliza os seguintes software e bibliotecas Python:

- [Python 2.7](https://www.python.org/download/releases/2.7/)
- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org/)
- [scikit-learn](http://scikit-learn.org/stable/)
- [Matplotlib](http://matplotlib.org/)

Você também precisará ter um software instalado para rodar e executar um [notebook Jupyter](http://ipython.org/notebook.html)
