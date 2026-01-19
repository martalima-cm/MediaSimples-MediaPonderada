# RELATÓRIO TÉCNICO 

Análise de Medidas de Tendência Central 

Data: 16 de janeiro de 2026 

Elaborado por: Análise Estatística - Pós-Graduação em Análise de Dados 

Objetivo: Demonstração prática dos conceitos de Média Simples e Média Ponderada 

 

# 1. RESUMO EXECUTIVO 

Este relatório apresenta a aplicação prática de medidas de tendência central em dois conjuntos de dados distintos: (1) faturamento mensal anual de uma empresa e (2) notas e pesos de atividades acadêmicas. O objetivo é demonstrar quando utilizar média simples versus média ponderada, evidenciando as diferenças metodológicas e interpretativas de cada abordagem. 

 

# 2. FUNDAMENTAÇÃO TEÓRICA 

2.1 Média Simples (Aritmética) 

A média simples é calculada pela soma de todos os valores dividida pela quantidade de observações, sendo aplicável quando todos os elementos têm igual importância na análise. 

Fórmula: 
```bash
Média Simples = (x₁ + x₂ + x₃ + ... + xₙ) / n 
``` 

Onde: 

x = valores observados 

n = número de observações 

## 2.2 Média Ponderada 

A média ponderada atribui pesos diferentes a cada observação, refletindo sua importância relativa no conjunto de dados. 

Fórmula: 
```bash
Média Ponderada = (x₁·p₁ + x₂·p₂ + ... + xₙ·pₙ) / (p₁ + p₂ + ... + pₙ) 
```

Onde: 

x = valores observados 

p = pesos atribuídos a cada valor 

 

# 3. ANÁLISE 1: FATURAMENTO MENSAL EMPRESARIAL 

## 3.1 Dados Coletados 

Faturamento mensal de uma empresa ao longo de 12 meses (valores em R$): 

Mês 

Faturamento (R$) 

Janeiro 

610.754.610,00 

Fevereiro 

320.593.685,00 

Março 

292.838.002,00 

Abril 

995.213.925,00 

Maio 

316.952.327,00 

Junho 

986.211.574,00 

Julho 

597.490.961,00 

Agosto 

261.705.462,00 

Setembro 

92.622.181,00 

Outubro 

747.909.201,00 

Novembro 

662.840.108,00 

Dezembro 

587.519.072,00 

## 3.2 Metodologia Aplicada 

Para este conjunto de dados, utilizou-se a MÉDIA SIMPLES, pois todos os meses possuem igual importância na análise do desempenho anual da empresa. 

### 3.3 Cálculos Realizados 

Soma Total dos Faturamentos: 

***Σ Faturamentos = R$ 6.472.651.108,00***
 

**Cálculo da Média:**

Média = 6.472.651.108,00 / 12 = R$ 539.387.592,33 
 

### 3.4 Resultados 

Média de Faturamento Mensal: R$ 539.387.592,33 

### 3.5 Análise Estatística Complementar 

- Valor Máximo: R$ 995.213.925,00 (Abril) 

- Valor Mínimo: R$ 92.622.181,00 (Setembro) 

- Amplitude: R$ 902.591.744,00 

- Coeficiente de Variação: Alto (84,5% da média) 

- Meses acima da média (7): Janeiro, Abril, Junho, Julho, Outubro, Novembro, Dezembro 

- Meses abaixo da média (5): Fevereiro, Março, Maio, Agosto, Setembro 

### 3.6 Insights Gerenciais 

Forte sazonalidade observada, com picos em Abril e Junho 

Setembro apresenta desempenho atípico (***apenas 17% da média anual***) 

Segundo semestre apresenta recuperação gradual até Dezembro 

Recomenda-se investigação das causas da baixa em Setembro 

 

# 4. ANÁLISE 2: AVALIAÇÃO ACADÊMICA COM PESOS 

4.1 Dados Coletados 

Sistema de avaliação com notas e pesos diferenciados: 

Atividade 

Nota 

Peso 

Atividade 1 

6,5 

20% 

Atividade 2 

7,5 

10% 

Atividade 3 

9,0 

5% 

Atividade 4 

9,0 

5% 

Atividade 5 

8,5 

5% 

Atividade 6 

8,0 

10% 

Atividade 7 

7,5 

15% 

Atividade 8 

7,5 

15% 

Atividade 9 

10,0 

5% 

Atividade 10 

9,0 

10% 

## 4.2 Metodologia Aplicada 

Neste caso, utilizou-se **MÉDIA PONDERADA**, pois as atividades possuem importâncias diferentes no sistema de avaliação, representadas pelos pesos percentuais. 

## 4.3 Cálculos Realizados 

***Método 1: Usando Percentuais*** 

Média Ponderada = (6,5×0,20) + (7,5×0,10) + (9,0×0,05) + (9,0×0,05) +  
                 (8,5×0,05) + (8,0×0,10) + (7,5×0,15) + (7,5×0,15) +  
                 (10,0×0,05) + (9,0×0,10) 
 
Média Ponderada = 1,30 + 0,75 + 0,45 + 0,45 + 0,425 + 0,80 + 1,125 +  
                 1,125 + 0,50 + 0,90 
 
Média Ponderada = 7,825 
 

***Método 2: Confirmação (usando pesos absolutos)***

Média Ponderada = (6,5×20 + 7,5×10 + 9,0×5 + 9,0×5 + 8,5×5 + 8,0×10 +  
                  7,5×15 + 7,5×15 + 10,0×5 + 9,0×10) / 100 
 
Média Ponderada = 782,5 / 100 = 7,825 
 

## 4.4 Resultados 

***Média Ponderada Final: 7,825 (aproximadamente 7,83)*** 

### 4.5 Comparação com Média Simples 

Para fins didáticos, se calculássemos a média simples (incorretamente): 

Média Simples = (6,5 + 7,5 + 9,0 + 9,0 + 8,5 + 8,0 + 7,5 + 7,5 + 10,0 + 9,0) / 10 
Média Simples = 82,5 / 10 = 8,25 
 

**Diferença: 0,425 pontos (5,15% de variação)** 

A média simples superestima o desempenho real, pois ignora que a Atividade 1 (com nota mais baixa) tem peso 20%, enquanto atividades com notas mais altas têm pesos menores. 

 

# 5. ANÁLISE 3: FOLHA SALARIAL EMPRESARIAL 

**5.1 Dados Coletados** 

Estrutura salarial da empresa com diferentes cargos e quantidades de funcionários: 

***Cargo*** 

***Qtd Funcionários*** 

Salário (R$) 

Diretor 

2 

19.000,00 

Gerente de vendas 

1 

11.000,00 

Gerente de tecnologia 

1 

12.000,00 

Assistente administrativo 

10 

2.900,00 

Programador web 

4 

5.400,00 

Programador mobile 

5 

5.800,00 

Designer 

4 

4.200,00 

Assistente de vendas 

8 

2.600,00 

Atendente 

14 

2.400,00 

Secretário 

4 

2.400,00 

***Total de Funcionários: 53***

## 5.2 Metodologia Aplicada 

Utilizou-se **MÉDIA PONDERADA**, pois o salário médio da empresa deve considerar a quantidade de funcionários em cada cargo. 

## 5.3 Cálculos Realizados 

Folha Salarial Total: 

Folha Total = (2×19.000) + (1×11.000) + (1×12.000) + (10×2.900) +  
             (4×5.400) + (5×5.800) + (4×4.200) + (8×2.600) +  
             (14×2.400) + (4×2.400) 
 
Folha Total = 38.000 + 11.000 + 12.000 + 29.000 + 21.600 + 29.000 +  
             16.800 + 20.800 + 33.600 + 9.600 
 
Folha Total = R$ 221.400,00 
 

**Salário Médio Ponderado:** 

**Salário Médio = 221.400,00 / 53 = R$ 4.177,36**
 

## 5.4 Resultados 

**Salário Médio da Empresa: R$ 4.177,36**

## 5.5 Comparação com Média Simples 

Se calculássemos a média simples dos salários (considerando apenas os valores únicos): 

Média Simples = (19.000 + 11.000 + 12.000 + 2.900 + 5.400 + 5.800 +  
                4.200 + 2.600 + 2.400 + 2.400) / 10 
 
Média Simples = 67.700 / 10 = R$ 6.770,00 
 

Diferença: R$ 2.592,64 (62% de superestimação!) 

A média simples distorce completamente a realidade salarial da empresa, pois ignora que: 

A maioria dos funcionários (36 de 53) ganha entre R$ 2.400 e R$ 2.900 

Os cargos de alta remuneração são minoria (apenas 4 funcionários) 

## 5.6 Análise da Distribuição Salarial 

Distribuição por Faixa: 

Até R$ 3.000: 36 funcionários (67,9%) 

R$ 3.001 a R$ 6.000: 13 funcionários (24,5%) 

Acima de R$ 10.000: 4 funcionários (7,5%) 

Mediana Salarial: R$ 2.600,00 (valor mais representativo do salário típico) 

 

# 6. QUADRO COMPARATIVO DAS METODOLOGIAS 

Critério 

Média Simples 

Média Ponderada 

Definição 

Todos os valores têm igual importância 

Valores têm importâncias diferentes 

Aplicação 

Análise 1 (Faturamento) 

Análises 2 e 3 (Notas e Salários) 

Quando usar 

Dados homogêneos sem hierarquia 

Dados com pesos, frequências ou importâncias 

Vantagem 

Simplicidade de cálculo 

Precisão e representatividade 

Desvantagem 

Ignora pesos e frequências 

Maior complexidade 

Exemplo de uso 

Temperatura média mensal 

Notas escolares, índices econômicos 

 

# 7. CONCLUSÕES 

## 7.1 Principais Achados 

Análise de Faturamento: A média simples de R$ 539,4 milhões representa adequadamente o faturamento mensal típico, porém a alta variabilidade indica necessidade de análise complementar de sazonalidade. 

Avaliação Acadêmica: A média ponderada de 7,83 reflete com precisão o desempenho considerando a importância relativa de cada atividade. O uso incorreto da média simples resultaria em superestimação de 5,15%. 

Análise Salarial: A média ponderada de R$ 4.177,36 representa fielmente a realidade da folha salarial. O uso da média simples (R$ 6.770,00) distorceria a análise em 62%, prejudicando decisões de gestão de pessoas. 

## 7.2 Recomendações Metodológicas 

Use MÉDIA SIMPLES quando: 

Analisar séries temporais homogêneas (faturamento, temperatura, vendas) 

Todos os elementos têm igual relevância 

Não há frequências ou pesos associados 

Use MÉDIA PONDERADA quando: 

Existem pesos ou importâncias diferentes (notas escolares, índices) 

Há quantidades/frequências associadas (salários por cargo) 

A precisão depende de considerar volumes ou relevâncias 

## 7.3 Considerações Finais 

A escolha adequada entre média simples e ponderada é fundamental para: 

Evitar distorções na análise de dados 

Tomar decisões gerenciais embasadas 

Comunicar resultados de forma precisa e transparente 

Manter a integridade analítica em estudos estatísticos 

A aplicação incorreta dessas medidas pode levar a conclusões equivocadas e decisões prejudiciais às organizações. 

 

# 8. REFERÊNCIAS TÉCNICAS 

Medidas de Tendência Central - Estatística Descritiva 

Análise de Dados Quantitativos - Pós-Graduação 

Métodos Estatísticos Aplicados à Gestão 


Documento elaborado para fins acadêmicos e demonstrativos.
 
Relatório técnico gerado em 16/01/2026 

 
