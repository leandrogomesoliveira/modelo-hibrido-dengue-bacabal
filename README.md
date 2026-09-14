# Modelo Híbrido para a Dinâmica da Dengue em Bacabal-MA

Este repositório contém os códigos computacionais utilizados na dissertação desenvolvida no Programa de Mestrado Profissional em Matemática Aplicada e Computacional da Universidade Estadual de Campinas (UNICAMP).

## Descrição

Os códigos implementam a metodologia computacional utilizada na modelagem da dinâmica da dengue em Bacabal-MA, combinando o modelo epidemiológico SEIR-SI com técnicas de aprendizado de máquina.

A abordagem utiliza dados epidemiológicos e climáticos e, no refinamento entomológico, dados do LIRAa.

## Arquivo principal

- `Script_Leandro_final.ipynb` — notebook desenvolvido em Python e executado no Google Colab, contendo a implementação computacional utilizada nas simulações e análises apresentadas na dissertação.

## Metodologia

A implementação computacional contempla:

- modelo epidemiológico SEIR-SI;
- integração numérica das equações diferenciais;
- utilização de temperatura e umidade como covariáveis;
- utilização do LIRAa no refinamento entomológico;
- rede neural artificial para determinação da taxa de transmissão;
- calibração do modelo híbrido;
- simulações numéricas e cenários prospectivos.

## Ambiente de execução

O código foi desenvolvido em Python e pode ser executado no Google Colab.

## Autor

Leandro Gomes Oliveira

Programa de Mestrado Profissional em Matemática Aplicada e Computacional  
Universidade Estadual de Campinas (UNICAMP)
