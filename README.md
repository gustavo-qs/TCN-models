# Previsão de Temperatura em Silos com Temporal Convolutional Network para Contornar Possíveis Falhas em Sensores de Temperatura Digitais

 - Aplicação do modelo padrão TCN em um ambiente univariado em 4 diferentes parametrizações visando a previsão de uma série temporal estacionária.

## Introdução
 - A análise da termometria é uma técnica utilizada na indústria agrícola para monitorar a temperatura
interna dos silos que armazenam grãos e outros produtos, sensores digitais instalados em cabos pên-
dulos são utilizados para esse fim. Entretanto, esses sensores podem sofrer consequências da má-
instalação elétrica da unidade da fazenda, o que pode gerar problemas como baixa capacitância, ater-
ramento inadequado e interferência no sinal elétrico ou até mesmo problemas na construção do sensor
que comprometem a qualidade e precisão da leitura da temperatura. Embora esses problemas muitas
vezes não sejam preocupantes, alguns sensores podem falhar na sua leitura, deixando um espaço do
silo sem a termometria. O presente trabalho tem como objetivo aplicar e analisar o comportamento do
modelo padrão de Temporal Convolutional Network (TCN) em dados univariados que deve ser capaz
de prever a temperatura que esses sensores afetados estariam indicando, fornecendo uma alternativa
para o usuário até que a situação seja resolvida. Para avaliar o desempenho do modelo, foram utiliza-
das métricas estatísticas, o Root Mean Square Error (RMSE), o Mean Squared Error (MSE) e o Mean
Absolute Error (MAE), fornecendo uma análise abrangente da precisão das previsões, com o melhor
e mais importante resultado obtendo 3,405 para o RMSE, 11,595 para o MSE e 1.805 para o MAE.
Este estudo busca contribuir para a solução de um problema comum na termometria de silos e pode
ter impacto significativo na indústria agrícola e na qualidade dos produtos alimentícios armazenados,
melhorando a qualidade de vida do consumidor final e facilitando o trabalho dos operadores do sistema
de termometria

---

**Citação:**
```
@article{Queiroz2023,
  author    = {Queiroz, Gustavo},
  title     = {Previsão de Temperatura em Silos com Temporal Convolutional Network para Contornar Possíveis Falhas em Sensores de Temperatura Digitais},
  year      = {2023},
  url       = {https://github.com/gustavo-qs/TCC},
}
```
---
