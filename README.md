# Algoritmos de Machine Learning para Classificação

Este notebook aplica os algoritmos de classificação apresentados no livro [An Introduction to Statistical Learning](https://hastie.su.domains/ISLP/ISLP_website.pdf.download.html) na base de dados de falência de companias disponível no Kaggle.
Os dados dessa base possuem 96 variáveis independentes, o que faz com que alguns algoritmos tenham performance ruim no grupo de treinamento e o tempo de estimação seja lento. Por isso, os escores dos seis primeiros componentes principais foram utilizados 
como variáveis preditoras, o que melhora muito a performance de alguns algoritmos como o naive bayes e o QDA. 

Dados: [Company Bankruptcy Prediction](https://www.kaggle.com/datasets/fedesoriano/company-bankruptcy-prediction)

Resultados: 
