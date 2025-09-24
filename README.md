# Como interpretar uma ação e valuation

## 1. Conceitos básicos

 Preço da ação: é o valor da última transação no mercado, ou seja, quanto você pagaria hoje para comprar a ação.
 Valor da ação: é o valor intrínseco, calculado com base nos benefícios futuros de caixa que a empresa deve gerar.
 Investimento: é considerado bom quando o valor estimado do ativo > preço atual no mercado.

   Ex.: Se você espera que a ação valha R\$ 50, mas está sendo negociada a R\$ 40, ela pode ser uma oportunidade de compra.
 Pensamento de longo prazo: compra-se pensando nos dividendos e na valorização futura.

---

## 2. Conceitos financeiros importantes

 Goodwill: representa a riqueza gerada pela empresa além do capital investido, ou seja, quanto a empresa vale mais do que o que foi aportado.
 Patrimônio líquido: reflete o passado da empresa; não é o valor de mercado atual ou futuro.
 Ativos: não necessariamente refletem valor; o que importa para valuation é o valor econômico futuro, baseado em premissas.

> Resumo: o valuation é futuro, enquanto patrimônio/ativos refletem o passado.

---

## 3. Fontes de estudo e pesquisa

 Listas de empresas unicórnio: The Complete List of Unicorn Companies
 Plataformas para estudo de ações: Invest.com

---

## 4. Custos de capital e CAPM

### 4.1 CAPM (Capital Asset Pricing Model)

O CAPM é usado para calcular a taxa de retorno exigida de uma ação, considerando risco de mercado:


Ke = Rf + \beta_j \times (Rm - Rf)


 Ke = retorno exigido da ação (Custo de Capital Próprio)
 Rf = taxa livre de risco (ex.: rendimento de renda fixa segura)
 Rm = retorno esperado da carteira de mercado
 βj = Beta da ação, mede a volatilidade da ação em relação ao mercado

---

### 4.2 Beta

 Beta por benchmark: padrão do mercado.
 Beta alavancado (Bl): considera a empresa com dívidas (risco econômico + financeiro):


Bl = Bu \times [1 + (P/PL) \times (1-IR)]


 Bl: Beta alavancado (empresa com dívida)
 Bu: Beta não alavancado (empresa sem dívida)
 P: Passivos onerosos (dívida)
 PL: Patrimônio líquido
 IR: Alíquota de Imposto de Renda

> Ex.: ajusta o risco da empresa conforme sua alavancagem financeira.

---

### 4.3 Exemplos de cálculo do custo de capital

Premissas do exemplo:

 Taxa livre de risco: 7%

 Prêmio de risco de mercado: 9,5% a.a.

 Custo de capital próprio alavancado:


Ke = 7\% + 0,95 \times 9,5\% = 16\%


 Custo de capital próprio sem dívida:


Ke = 7\% + 0,65 \times 9,5\% = 13,2\%


 Prêmio pelo risco financeiro (dívida):


16\% - 13,2\% = 2,8\%


> Ou seja, o risco financeiro (dívida) adiciona 2,8% ao custo do capital próprio.

---

## 5. Fluxo de Caixa Descontado (FCD)

 FCD: método para calcular o valor da empresa com base no fluxo de caixa futuro, descontando pelo custo de capital.
 É a principal técnica de valuation de ações e empresas.

> A lógica: dinheiro no futuro vale menos hoje, por isso se desconta pelo custo de capital (Ke).

---

Show, Raul 👌 Vou dar continuidade na sua estrutura organizada, numerando a partir do item 6, já que você tinha parado no 5. Fluxo de Caixa Descontado (FCD). Vou organizar as novas anotações em blocos bem claros, destacando fórmulas e observações.

---

# Como interpretar uma ação e valuation

(continuação das suas anotações)

---

## 6. CAPM Ajustado

O CAPM tradicional pode ser ajustado para refletir fatores adicionais como risco-país, inflação e tamanho da empresa.

Fórmula:

$$
Ke = Rf + \beta \times (Rm - Rf) + RISCO_{br} + (INF_{br} - INF_{usa}) + SP
$$

 Rm: taxa de retorno da carteira de mercado (benchmark: S\&P, NYSE)
 Rf: taxa livre de risco (benchmark: T-Bonds)
 INF: taxa de inflação (país vs EUA)
 β: beta (média ponderada de empresas comparáveis)
 SP: Size Premium (prêmio pelo porte da empresa)

---

## 7. Custo de Capital de Terceiros e Estrutura de Capital

 Custo de capital de terceiros: vem da dívida (obrigação contratual).
 Custo total de capital (WACC): média ponderada entre capital próprio e de terceiros.

Estrutura ótima de capital: é aquela em que o WACC é o menor possível, maximizando o valor da empresa.

📌 Fontes de dados:

 ValorData → SELIC, CDI, etc.
 “Betas by Sector (US)” → fornece beta alavancado/não alavancado e prêmio de risco de mercado.
 Instituto Assaf → dados de Ibovespa, IPCA, Selic.

---

## 8. Métodos de Valuation

### 8.1 Método Contábil

 Mostra o valor da empresa naquele momento.
 Reflete apenas descontinuidade, não considera oportunidades de crescimento.

Tipos:

 Valor Patrimonial: valor do PL do balanço.
 Valor de Liquidação: ativos – passivos (se a empresa encerrasse hoje).

---

### 8.2 Método de Valor de Mercado

 Valor visto no dia a dia na bolsa.
 Fórmula:

  
  Valor = \text{Nº de ações} \times \text{Cotação}
  
 Limitação: no Brasil há alta concentração de capital → pode distorcer o valor.

---

### 8.3 Método de Múltiplos

 Avalia a empresa por múltiplos (ex.: EV/EBITDA, P/L etc.).
 Baseia-se em comparação com empresas semelhantes.
 Limitações:

   Não considera crescimento futuro.
   Difícil encontrar empresas realmente comparáveis.

---

### 8.4 Método do Fluxo de Caixa Descontado (FCD)

 O mais aceito e recomendado.
 Considera expectativas futuras de caixa, trazendo a valor presente.
 Inclui valor de continuidade da empresa.
 Abrange todos os aspectos (crescimento, risco, retorno).

---

### 8.5 Método da Stern Stewart & Co (Lucro Econômico / EVA)

Considerado um dos mais completos. Avalia o lucro econômico da empresa.

#### Principais fórmulas:

 WACC:


WACC = We \times Ke + Wi \times Ki


 ROE:


ROE = ROI + (ROI - Ki) \times \frac{P}{PL}



ROE = \frac{LL}{PL}


 EVA (Economic Value Added):


EVA = NOPAT - WACC \times Investimento



EVA = (ROI - WACC) \times Investimento



EVA = LL - Ke \times PL



EVA = (ROE - Ke) \times PL


 Goodwill:


Goodwill = \frac{EVA}{WACC}


 Valor da Empresa:


Valor = Investimento + Goodwill


 ROI (ou ROIC/ROCE):


ROI = \frac{NOPAT}{Investimento}



ROI = \text{Margem Operacional} \times \text{Giro do Investimento}


 Margem operacional:


\frac{NOPAT}{Receita}


 Giro do investimento:


\frac{Receita}{Investimento}


---

### 8.6 Estrutura prática (DF e DRE ajustada)

 Receita operacional líquida – Custo das vendas = Lucro Bruto
 Lucro Bruto – Despesas operacionais líquidas = Lucro antes do resultado financeiro
 EBITDA: Lucro antes do resultado financeiro + Depreciação
 EBT: Lucro antes do resultado financeiro – Depreciação
 NOPAT restrito: EBIT – IR e CSLL (só da atividade principal)
 NOPAT amplo: NOPAT restrito + Receita financeira – IR/CSLL
 Lucro líquido: NOPAT amplo – Despesas financeiras + Benefício fiscal (IR das despesas financeiras)

---
