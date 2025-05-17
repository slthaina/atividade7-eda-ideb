# FACULDADE DE COMPUTAÇÃO E INFORMÁTICA (FCI)

## 👩‍💻 Autora

- **Thainá Silva Leite** – RA: 10730503  

---

# Projeto de Análise Exploratória de Dados (EDA):  
## Análise do IDEB e das Desigualdades Educacionais no Ensino Público do Município de São Paulo

---

# Objetivo
Investigar como o Índice de Desenvolvimento da Educação Básica (IDEB) varia entre os diferentes distritos da cidade de São Paulo, analisando sua evolução ao longo do tempo e identificando fatores socioeconômicos correlacionados, especialmente aqueles representados pelo Índice de Desenvolvimento Humano Municipal (IDHM).

# Dados Utilizados
IDEB: Instituto Nacional de Estudos e Pesquisas Educacionais Anísio Teixeira (INEP)

IDHM: Programa das Nações Unidas para o Desenvolvimento (PNUD)

# Metodologia
Exploração Inicial dos Dados: Descrição das variáveis, verificação de dados ausentes e outliers.

Resumo Estatístico: Cálculo de medidas como média, mediana, moda, mínimo, máximo, quartis e desvio padrão.

Visualizações de Dados: Criação de histogramas, boxplots, gráficos de dispersão e mapas de calor.

Teste de Normalidade: Aplicação do teste de Kolmogorov-Smirnov para verificar a normalidade de variáveis numéricas.

Relações Entre Variáveis: Análise de correlação entre variáveis numéricas.

Conclusão: Identificação de padrões, anomalias e insights relevantes.

# Resultados
Identificação de correlações significativas entre o IDEB e os componentes de renda e educação do IDHM.

Visualizações que destacam as desigualdades educacionais entre os distritos de São Paulo.

Insights sobre fatores socioeconômicos que influenciam o desempenho educacional.

---

## Ambiente de Desenvolvimento

Projeto desenvolvido em **Jupyter Notebook**, utilizando a linguagem **Python 3.13**.

**Bibliotecas principais:**

- `pandas`, `numpy` – Manipulação de dados  
- `matplotlib`, `seaborn` – Visualização gráfica  
- `scikit-learn` – Análise estatística e modelagem  
- `geopandas` – Análise espacial  

---

## Como Executar

1. Clone o repositório:
```bash
git clone git clone https://github.com/slthaina/atividade7-eda-ideb.git
cd atividade7-eda-ideb
```

2. (Opcional) Crie um ambiente virtual:
```bash
python -m venv venv
source venv/bin/activate  # Linux/macOS
venv\Scripts ctivate     # Windows
```

3. Instale as dependências:
```bash
pip install -r requirements.txt
```

4. Execute os notebooks:
```bash
jupyter notebook
```
Acesse a pasta `notebooks/` e abra os arquivos `.ipynb`.

---

##  Bibliotecas

As bibliotecas necessárias para rodar o projeto são:

- pandas
- numpy
- matplotlib
- seaborn

---

## Conclusão Esperada

Espera-se que distritos com menor desenvolvimento humano apresentem, em média, IDEBs mais baixos — reforçando a necessidade de políticas públicas que integrem aspectos educacionais e sociais.

