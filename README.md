# 📊 Análise de Churn e Retenção de Clientes (Telecom)

## 📌 Visão Geral do Projeto
Este projeto tem como objetivo analisar o comportamento de cancelamento de clientes (churn) em uma empresa de telecomunicações, identificando os principais fatores que levam à perda de clientes e propondo estratégias direcionadas para retenção.

---

## 🔍 Perguntas de Negócio Respondidas
1. Qual é a taxa geral de cancelamento de clientes da base?
   Resultado: A taxa geral de Churn é de **26,54%** (1.869 clientes cancelados).
3. Quais formas de pagamento concentram o maior volume de cancelamentos?
   Resultado: Contratos mensais (`Month-to-month`) pagos via Cheque Eletrônico (`Electronic check`) lideram com **994 cancelamentos** (representando mais de 53% de todo o churn).
4. Como o tempo de contrato (tenure) influencia a decisão de cancelamento?
   Resultado: A média de permanência dos clientes que cancelam é de **18 meses**, contra **37,6 meses** dos clientes retidos.

---

## 🛠️ Tecnologias e Ferramentas Utilizadas
- **SQL (SQLite):** Agregações avançadas, subconsultas e agrupamento de dados.
- **Python (Pandas):** Leitura de dados, limpeza, padronização de colunas e médias operacionais.
- **Google Colab:** Ambiente de execução e desenvolvimento do código.

---

## 💡 Recomendações Estratégicas para o Negócio
- **Migração de Forma de Pagamento:** Incentivar a migração de clientes em cheque eletrônico para débito automático ou cartão de crédito através de pequenos descontos ou benefícios na fatura.
- **Campanhas de Engajamento Precoce:** Criar ações de onboarding e retenção direcionadas aos clientes nos primeiros 18 meses de contrato.

---

## 📂 Como visualizar a análise
Os scripts e consultas executados estão organizados na pasta deste repositório.
