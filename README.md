# Case Técnico de Analytics — Mevo (Saúde+)

## Objetivo
Explorar a base do case, calcular métricas de **prescrição**, **abertura** e **conversão** e entender variações por **especialidade**, **medicamento**, **gerações** **etc**.

## Dados usados
- `prescricaomedicamento.csv` (nível de medicamento, com flags de abertura/conversão)
- `medicamentos.csv` (dicionário de medicamentos)
- `medicos.csv` (atributos de médicos)

## O que eu fiz
1. **Ingestão e limpeza**
   - Padronização de colunas, datas e chaves (ids).
   - Remoção de duplicidades e ajustes de qualidade.

2. **Métricas base**
   - Cálculo de **open rate** e **conversão** por dia/semana.
   - Séries temporais para volumetria de prescrições.

3. **Cortes analíticos**
   - **Especialidade**: ranking e comparação de taxas.
   - **Medicamento**: contribuição em **pontos percentuais (p.p.)** para quedas/altas de conversão (ex.: itens abaixo da média).
   - **Gerações**
   - **Período do dia**: madrugada, manhã, tarde, noite (comparação de conversão).

4. **Conclusão**
   - Consolidação das principaisconclusões.
   - Slide final com “Implicação” e “Próximos passos”.
