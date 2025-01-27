#  **Análise de fatores associados ao transtorno depressivo na população americana: Uma abordagem com dados do NHANES**
![image](https://github.com/user-attachments/assets/5ebc6d32-c97c-41f5-bc33-87ddd45b55e0)


## 📌 Descrição:
Este repositório contém um projeto de análise de dados focado em entender padrões de depressão nos Estados Unidos usando dados do NHANES (National Health and Nutrition Examination Survey). Utilizamos uma abordagem exploratória e visualização de dados para identificar correlações entre variáveis, como gênero, nível educacional e padrões alimentares, com os níveis de depressão relatados.

📊[Acesse o meu notebook aqui](https://github.com/josieleferreira/Case_Depressao/blob/main/notebook/Case_Depress%C3%A3o.ipynb)

📃[Acesse a minha apresentação aqui](https://github.com/josieleferreira/Case_Depressao/blob/main/reports/Case%20Depress%C3%A3o.pdf)



## 🔧 Como executar localmente:

1. Clone o repositório:
    
    ```
    https://github.com/josieleferreira/Case_Depressao.git
    ```
    



## 🔧 Ferramentas e Tecnologias:

- **Python**
- **Bibliotecas principais**:
    - `pandas` para manipulação de dados
    - `matplotlib` e `seaborn` para visualizações
    - `numpy` para cálculos numéricos
    - `scipy` para testes estatísticos


## 🔍 Objetivos do projeto:

1. Analisar a distribuição dos níveis de depressão (variáveis `DPQ_ALL_num | DPQ_ALL_cat`).
2. Identificar relações entre depressão e:
    - Gênero (`RIAGENDR`)
    - Faixa etária (`RIDAGEYR`)
    - Nível educacional (`DMDEDUC_cat`)
    - Padrões alimentares (`HEI2015_TOTAL_SCORE`).
3. Criar visualizações que ilustrem os principais achados.
4. Propor insights baseados nos resultados.


## 🔄 Fluxo de trabalho:

1. **Pré-processamento dos dados**:
    - Tratamento de valores ausentes.
    - Criação de variáveis derivadas, como `DPQ_ALL_num` e `DPQ_ALL_cat` (categorização de escores de depressão).
2. **Exploração Inicial**:
    - Estatísticas descritivas.
    - Visualizações gerais para identificar tendências.
3. **Análise Detalhada**:
    - Comparações entre grupos usando testes estatísticos (t-test, ANOVA).
4. **Relatório e Visualizações**:
    - Gráficos finais e interpretação dos resultados.

    

## 📊 Insights preliminares:

- Níveis mais altos de depressão são mais frequentes em indivíduos com menor nível educacional.
- Uma dieta rica em vegetais e frutas parece estar associada a escores mais baixos de depressão.
- Mulheres relatam escores mais altos de depressão em comparação aos homens.



## 🛠️ Contribuições:

Contribuições são sempre bem-vindas! Por favor, envie um pull request ou abra uma issue para discutir melhorias.



## 🌐 Referências:

- [NHANES](https://www.cdc.gov/nchs/nhanes/index.htm): Fonte de dados.
