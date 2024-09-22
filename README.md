# Análise do Comportamento de Ações Brasileiras Durante a Pandemia de COVID-19 (2019-2021)
Este projeto faz parte de um estudo que analisa o comportamento de um portfólio de ações brasileiras no período entre 2019 e 2021, com foco nos impactos da pandemia de COVID-19 sobre a volatilidade, o desempenho das empresas e a diversificação da carteira.

## 1. Objetivos
O principal objetivo deste estudo é entender como a crise gerada pela pandemia afetou o risco e a rentabilidade de 10 ações brasileiras de diferentes setores. A análise foi conduzida com foco em três questões centrais:

**1. Análise da Volatilidade**: Comparar a volatilidade (desvio padrão dos retornos diários) dos ativos antes e depois do início da pandemia.

**2. Impacto Setorial**: Avaliar como diferentes setores foram impactados pela pandemia em termos de volatilidade e recuperação dos preços.

**3. Diversificação da Carteira**: Investigar o grau de diversificação do portfólio e como a correlação entre os ativos foi afetada pelo período de crise.

## 2. Metodologia
A análise foi realizada utilizando Python e as bibliotecas de dados e visualização mais comuns (Pandas, Matplotlib, Seaborn, etc.). O estudo inclui:

* **Análise Exploratória de Dados (EDA)**: Visualizações e estatísticas descritivas para entender o comportamento dos preços e retornos ao longo do período.
* **Cálculo de Volatilidade**: Medida através do desvio padrão dos retornos diários.
* **Diversificação**: Avaliação da correlação entre os ativos do portfólio antes e depois da pandemia.

## 3. Resultados
**1. Aumento Generalizado da Volatilidade**
Todas as ações analisadas apresentaram um aumento na volatilidade após o início da pandemia, com destaque para os setores de varejo e imobiliário, que sofreram os maiores impactos.

**2. Diferenças Setoriais no Risco**
Enquanto setores como o varejo alimentar (CRFB3.SA) mantiveram uma volatilidade relativamente estável, setores mais expostos a variações econômicas (ex: petróleo e varejo tradicional) experimentaram aumentos significativos no risco.

**3. Diversificação da Carteira**
A correlação entre os ativos aumentou durante a pandemia, limitando os benefícios da diversificação no período de crise. Isso resultou em uma maior sincronização entre os movimentos dos preços das ações.

## 4. Próximos Passos
Este projeto é a **Parte 1** de um estudo mais amplo. **Na Parte 2**, será aplicada a metodologia do **Value at Risk (VaR)** para medir o risco de perdas potenciais da carteira em diferentes cenários. A introdução do VaR permitirá uma análise mais aprofundada dos riscos que o portfólio enfrenta em condições de mercado adversas.
