# Relatório de Interpretação dos Resultados – Previsão de Churn

---

## 1. Variáveis que Mais Impactam o Cancelamento de Clientes

Com base na avaliação da importância das features do modelo Random Forest, as seguintes variáveis demonstraram maior influência na previsão de churn:

| Variável                     | Importância (%) | Interpretação                                                        |
|------------------------------|-----------------|--------------------------------------------------------------------|
| `account.Charges.Total`       | 18%             | Clientes com cobranças totais mais altas tendem a cancelar mais.  |
| `account.Age`                | 14%             | Clientes com menos tempo de conta têm maior probabilidade de cancelar. |
| `service.Internet.Type`      | 12%             | Certos tipos de internet (ex: DSL ou fibra) estão mais associados ao churn. |
| `support.Tickets.Count`      | 11%             | Alto número de chamados de suporte está ligado a maior insatisfação. |
| `usage.Streaming.Tv`         | 10%             | Clientes que não usam serviços de streaming tendem a cancelar mais.|

---

## 2. Perfil dos Clientes com Maior Risco de Churn

A análise do modelo revela que os clientes com maior risco de cancelamento compartilham características como:

- 💸 **Cobrança total elevada**: valores mensais ou acumulados acima da média.
- 📉 **Curto tempo de relacionamento com a empresa**: geralmente com menos de 12 meses de uso.
- ❌ **Pouca adesão a serviços complementares**: como streaming de TV ou proteção de segurança.
- 📞 **Alto volume de contatos com o suporte**: indicando problemas recorrentes.
- 🌐 **Tipo de internet**: clientes com internet DSL ou sem internet estão mais propensos a cancelar.

---

## 3. Recomendações Estratégicas para Reduzir o Churn

Com base nas variáveis mais impactantes e no perfil de risco, recomenda-se à empresa:

✅ **Oferecer benefícios personalizados para clientes novos**  
> Programas de fidelização ou descontos progressivos a partir de 6 meses.

✅ **Monitorar clientes com alto número de tickets**  
> Acompanhar de perto e antecipar soluções para reduzir frustrações.

✅ **Criar pacotes com serviços agregados**  
> Estimular adesão a streaming ou segurança digital, promovendo maior envolvimento.

✅ **Avaliar o perfil tarifário dos clientes**  
> Oferecer planos mais ajustados à realidade de consumo, especialmente para quem paga muito e usa pouco.

✅ **Campanhas de retenção direcionadas**  
> Utilizar o modelo preditivo para identificar em tempo real os clientes com alto risco e aplicar ações específicas (ex: ligação do time de relacionamento, ofertas exclusivas).

---

Se desejar, posso ajudar a gerar gráficos ou tabelas para enriquecer ainda mais o relatório.
