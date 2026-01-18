# Dashboard de Vendas (Excel) — Xbox Subscriptions

## Sobre o projeto
Este repositório contém um **dashboard de vendas feito no Excel** com base em uma planilha de assinaturas (Xbox), com o objetivo de transformar dados brutos em **indicadores e gráficos** para facilitar a análise e a tomada de decisão.

## Base de dados
Arquivo de entrada: `base.xlsx`  
Principais campos utilizados:
- Plano (Plan)
- Data de início (Start Date)
- Tipo de assinatura (Subscription Type)
- Renovação automática (Auto Renewal)
- Valores (Subscription Price, Add-ons, Coupon Value, Total Value)

## O que foi construído no Excel
O arquivo `dashboard_vendas_xbox.xlsx` possui 4 abas:

- **Assets**: referência visual (paleta/estilo).
- **Bases**: dados brutos importados.
- **Cálculos**: tratamento/normalização e tabelas-resumo (KPIs e agregações).
- **Dashboard**: painel com KPIs e gráficos.

### KPIs (indicadores)
- Total de receita (R$)
- Total de assinantes
- Ticket médio
- % de Auto Renewal (Yes)
- % de EA Play (Yes)
- % de Minecraft (Yes)

### Gráficos
- Receita por Plano
- Receita por Tipo de Assinatura
- Receita mensal (por mês de início)
- Assinantes por Plano

## Como reproduzir
1. Baixe/clone este repositório.
2. Abra o arquivo **`dashboard_vendas_xbox.xlsx`** no Excel (recomendado: Excel 2016+ / Microsoft 365).
3. Caso o Excel peça para habilitar edição/atualização, clique em **Habilitar**.

## Estrutura sugerida do repositório
```
/
├─ README.md
├─ base.xlsx
└─ dashboard_vendas_xbox.xlsx
```

## Observações
- Os valores foram padronizados para formato numérico (R$) na aba **Cálculos** para permitir somas e gráficos.
- Caso você substitua a base, basta manter as colunas com os mesmos nomes para continuar funcionando.
