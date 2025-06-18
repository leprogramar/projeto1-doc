# projeto1-doc
Aplicação de Algitmos de Machine Learning para Predição da Temperatura Interna ao Final da Corrida de 10km

Este projeto se dedica à aplicação de modelos de machine learning para prever a temperatura interna ao término de uma corrida autocontrolada de 10km.

A base de dados utilizada neste trabalho é proveniente do artigo de [Andrade et al. (2023)](https://pmc.ncbi.nlm.nih.gov/articles/pmid/37018484/), com os dados brutos disponíveis pelos autores diretamente em https://doi.org/10.6084/m9.figshare.21508239.

Previamente à modelagem, a base de dados foi submetida a um pré-processamento que incluiu a remoção de variáveis não utilizada aos modelos, a alteração da estrutura de dados das variáveis para formatos mais adequados, a eliminação de caracteres inválidos e a substituição de vírgulas por pontos para padronização numérica. Detalhes sobre estas transformações estão documentados no notebook pre-processamento.ipynb , localizado em [/home/lafise/Desktop/Samuel/leticiaag/pre-processamento.ipynb](https://github.com/leprogramar/projeto1-doc/blob/main/pre-processamento.ipynb). A partir dos dados pré-processados, foram geradas três bases de dados distintas, cada uma configurada para replicar os modelos de variáveis propostos pelos autores originais: Base de Dados 1 (10 variáveis), a Base de Dados 2 (8 variáveis) e a Base de Dados 3 (5 variáveis).

O objetivo primário deste trabalho é avaliar a performance e otimização dos algoritmos de Decision Tree, Random Forest, XGBoost e LASSO Regression sobre as três bases de dados.

